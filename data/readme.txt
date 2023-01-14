
inputs/ contains the action and predicate specification files.
outputs/ contains the computed plans, in plain text format.

Each directory under inputs/ contains three files:

actions.tvp    		contains the action specification
init_abs.tvs 		contains the initial concrete structure
predicates_abs.tvs 	contains the predicates and integrity
			constraints of the domain.


Each of these files is in TVLA's input formats. A detailed description
of these formats can be found in the TVLA manual (tvla_manual.pdf),
also stored in the directory containing this readme for convenience.

TVLA can be downloaded and installed from
http://www.math.tau.ac.il/~tvla/tvla-2-alpha.jar.

Note that this is version 2 of TVLA; a more recent version is available but
not used in our implementation.
