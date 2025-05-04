Artifacts

## Summary

This is a concept aimed at improving performance for large directories that are regularly recompiled. The command line parameters have been implemented, waiting for feature implementation to follow, but those were removed from version 1.0 of the Transpiler, as implementation of the feature has been scraped. It is possible to implement the feature of producing artifacts in some limited capacity in the future - for example to produce only, for debugging purposes.

A major drawback is the inability to easily and fast perform checks to see if all the files in a large directory are unchanged ever since an artifact was generated, as reading many files texts and calculating check-sums will not be particularly faster, greatly diminishing the benefits of such a feature. Users then can be responsible for deleting out of date artifacts, but this adds to complexity and things that can go wrong for the user.

The idea is that, once we compile all the files in a subfolder to an unfold for example, we can serialize that unfold to a file, named with a hash of the folder path, with the `.art` extention, and place it in the folder, or in a different artifacts folder structure. The next time we are parsing this large folder, we simply deserialize the unfold and integrate it into the larger unfold being translated. We use ArtifactsPath parameter to set a path to artifacts folder, if it should be different, and an AtrifactMode enum to indicate weather we will be taking (deserializing) artifacts or making new ones. Use will take if available and make if not available. No will ignore artifacts.


## ArtifactMode enum

Indicates how the Transpiler uses artifacts.
MakeOnly - Only create artifacts, but not consume.
TakeOnly - Only consume artifacts if available, but do not create new.
Use - Both create and consume artifacts.
No - Do not use artifacts.

	ArtifactMode

		.MakeOnly
		.TakeOnly
		.Use
		.No

## Cons

* Adds a layer of complexity for the user
* Adds a layer of complexity for implementation and different versions interoperability
* Adds an overhead on maintaining such directories
* Can create situations with out of date content proliferating