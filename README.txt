TECHTREE ENTRIES
bbase-assim.odf				1	borpod1.odf	// Borg Assimilation Nexus
borg-bluebeam-station.odf	0				// Borg Auto-Assimilator - Station variant
bturret-assim.odf			1	borpod1.odf	// Borg Assimilation Turret
bturret-assim-refit.odf		1	borpod1.odf	// Borg Assimilation Turret Refit

HOTKEY ENTRIES
# Assimilation Nexus - A is for "Assimilation"
bc_bbase-assim {
	+ keyboard	A
	- keyboard	Control
	- keyboard	Shift
	- keyboard	Alt
}

BUTTON ENTRIES
@reference=128
@tmaterial=interface
b_bbase-assim			gbrefit1	0	64	64	64	#	1	2
b_bturret-assim-refit	gbrefit1	64	64	64	64	#	2	2
#reference=64
#b_borg-bluebeam-station			gbbaabore00		0	0	64	64		

CONSTRUCTOR ENTRIES
Included for your convenience are ODFs for the vanilla Borg constructor,
and a new ODF that includes an entry for the Assimilation Nexus.
However, if you wish to just add the entry yourself,
the line is provided below:

buildItem13 = "bbase-assim.odf"
