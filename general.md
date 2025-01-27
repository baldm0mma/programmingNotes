@kevin: what is the 'prerelease' metadate for? When have we used it in the past, how are we using it now?
@self: what is the product 'grafana-pro'? How does it differ from 'grafana-entreprise'?
@kevin/backport_action/backport.yml: why in the config yml do we have to checkout the whole repo, instead of targeting only the backport code itself?
@self: when should I use or not use a pointer in GO?
@kevin/@self: what's the difference between tagging with TAG and DRONE_TAG?
@self: are the uses of interfaces in GO only for testing? or do they have other uses? is there a JS/TS equivalent?
@kevin: how does the actual build process run? i mean, i know grafana-build has all our build tooling; but does grafana have a docker/makefile that downloads the build tools and then uses them to build the various binaries?
@self: how does promoting from main work when building from other tags? also, why dn't we just always use main as the target for building?
@self: bash script for printing and formatting file structure: find . -not -path "*/.git/*" -not -path "./.git" | sed -e "s/[^-][^\/]*\// |/g" -e "s/|\([^ ]\)/|-\1/"
@self: how are terraform and ansible used differently?
@self: what is absolutely necessary for grabpl? what can we remove easily?
@self: how do we add de facto dependabot scanning to all pertinent repos?
@self: what bumps are woth persuing?
@self: remove dependabot scanning for grafana-security-mirror?
