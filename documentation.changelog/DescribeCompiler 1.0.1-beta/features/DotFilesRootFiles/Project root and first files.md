	Project root and first files
	
	The one with the filename starting with a dot, otherwise the first one.
	In strings, it is the first one.
	
	
	

	The project-root directive tagged file is parsed as root. If not, the alphabetically first file
	in the parse folder is. TODO - check if we start from parse folder root file?
	Special symbol prefix vs dot prefix vs directive method
	
	Needs to be root file in the initial dir, as we can include other projects - first root directive will take effect, others will
	be skipped.

	directives ->
		project-root,
		language-version <1.0>,
		namespace <radiowatch>;

	Radio playlists <.rnode> ->

		Bulgarian {comment},
		Radio 1 Rock playlist <.bg.onerock>,
		Radio Energy playlist <.bg.energy>,
		Nova News playlist <.bg.novanews>,
		Radio City playlist <.bg.city>,
		Radio Veselina playlist <.bg.veselina>;