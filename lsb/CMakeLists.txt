# This Source Code Form is subject to the terms of the Mozilla Public
# License, v. 2.0. If a copy of the MPL was not distributed with this
# file, You can obtain one at http://mozilla.org/MPL/2.0/.

cmake_minimum_required(VERSION 3.0)
project(lsb VERSION 1.1.0 LANGUAGES C)
set(CPACK_PACKAGE_DESCRIPTION_SUMMARY "Utility modules for lua_sandbox")
set(CPACK_DEBIAN_PACKAGE_DEPENDS "luasandbox (>= 1.0.1)")
include(sandbox_module)
