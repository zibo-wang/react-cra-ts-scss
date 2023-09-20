workspace(name = "react-cra-ts-scss")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "io_bazel_rules_sass",
    sha256 = "9dcfba04e4af896626f4760d866f895ea4291bc30bf7287887cefcf4707b6a62",
    strip_prefix = "rules_sass-1.26.3",
    # Make sure to check for the latest version when you install
    url = "https://github.com/bazelbuild/rules_sass/archive/1.26.3.zip",
)

# Setup Bazel NodeJS rules.
# See: https://bazelbuild.github.io/rules_nodejs/install.html.

# Setup repositories which are needed for the Sass rules.
load("@io_bazel_rules_sass//:defs.bzl", "sass_repositories")

sass_repositories()
