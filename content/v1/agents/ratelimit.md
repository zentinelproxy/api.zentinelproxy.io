+++
title = "ratelimit"
template = "api/agent-detail.html"

[extra]
name = "ratelimit"
# Retired from the bundle (zentinel 26.10_8): no longer in bundle-versions.lock,
# so the version is the last release instead of the lock's pin.
version = "0.3.0"
repository = "zentinelproxy/zentinel-agent-ratelimit"
binary_name = "zentinel-ratelimit-agent"
protocol_version = "v2"
description = "Retired: rate limiting is built into Zentinel (policies { rate-limit { ... } }). Last release 0.3.0; `zentinel bundle install ratelimit` says so instead of installing it."
author = "Zentinel Core Team"
license = "Apache-2.0"
status = "deprecated"
category = "core"
tags = ["security", "traffic", "deprecated"]
min_zentinel_version = "26.01.0"
bundle_group = "Core agents"
+++
