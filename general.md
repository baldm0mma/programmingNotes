@kevin: what is the 'prerelease' metadate for? When have we used it in the past, how are we using it now?
@self: what is the product 'grafana-pro'? How does it differ from 'grafana-entreprise'?
@kevin/backport_action/backport.yml: why in the config yml do we have to checkout the whole repo, instead of targeting only the backport code itself?
@self: when should I use or not use a pointer in GO?
@kevin/@self: what's the difference between tagging with TAG and DRONE_TAG?
@self: are the uses of interfaces in GO only for testing? or do they have other uses? is there a JS/TS equivalent?
@kevin: how does the actual build process run? i mean, i know grafana-build has all our build tooling; but does grafana have a docker/makefile that downloads the build tools and then uses them to build the various binaries?
@self: how does promoting from main work when building from other tags? also, why dn't we just always use main as the target for building?
@self: bash script for printing and formatting file structure: .
 |-migrate-open-prs
 | |-README.md
 | |-handle_prs.go
 | |-handle_prs_test.go
 | |-main.go
 |-go.mod
 |-github-release
 | |-create_release.go
 | |-README.md
 | |-create_release_test.go
 | |-main.go
 | |-action.yml
 | |-main_test.go
 |-community-release
 | |-README.md
 | |-main.go
 | |-action.yml
 | |-main_test.go
 |-ci
 | |-main.go
 |-auto-milestone
 | |-README.md
 | |-main.go
 | |-action.yml
 | |-main_test.go
 |-backport
 | |-embed.go
 | |-testdata
 | | |-comment.txt
 | |-comment.go
 | |-event.go
 | |-release_branches_test.go
 | |-release_branches.go
 | |-exec.go
 | |-backport.go
 | |-cherrypick.go
 | |-comment.tmpl
 | |-cherrypick_test.go
 | |-backport_test.go
 | |-main.go
 | |-action.yml
 |-Dockerfile.dagger
 |-tools.go
 |-go.sum
 |-README.md
 |-update-changelog
 | |-main.go
 | |-action.yml
 |-.github
 | |-CODEOWNERS
 | |-workflows
 | | |-remove-milestone.yml
 | | |-bump-version.yml
 | | |-pull_request.yml
 | | |-close-milestone.yml
 | | |-codeowners-validator.yml
 | | |-main.yml
 | | |-migrate-open-prs.yml
 | |-dependabot.yml
 |-pkg
 | |-changelog
 | | |-parser_test.go
 | | |-renderer_test.go
 | | |-fileupdater.go
 | | |-renderer.go
 | | |-loader.go
 | | |-fileupdater_test.go
 | | |-builder.go
 | | |-parser.go
 | | |-builder_test.go
 | | |-loader_test.go
 | |-versions
 | | |-version_branch.go
 | | |-version_branch_test.go
 | | |-regex.go
 | |-ghgql
 | | |-genqlient.graphql
 | | |-generated.go
 | | |-github.schema.graphql
 | | |-ghgql.go
 | | |-milestones.go
 | | |-pullrequests.go
 | | |-README.md
 | | |-genqlient.yaml
 | |-community
 | | |-options.go
 | | |-search.go
 | | |-post_test.go
 | | |-community.go
 | |-toolkit
 | | |-toolkit.go
 | | |-usage_metrics_test.go
 | | |-usage_metrics.go
 | |-git
 | | |-repo.go
 |-catalog-info.yaml
