[Luau](https://luau.org) (lowercase u, /ˈlu.aʊ/) is a fast, small, safe, gradually typed embeddable scripting language derived from Lua.

It is designed to be backwards compatible with Lua 5.1, as well as incorporating some features from future Lua releases, but also expands the feature set (most notably with type annotations). Luau is largely implemented from scratch, with the language runtime being a very heavily modified version of Lua 5.1 runtime, with completely rewritten interpreter and other performance innovations. The runtime mostly preserves Lua 5.1 API, so existing bindings should be more or less compatible with a few caveats.

Luau is used by Roblox game developers to write game code, as well as by Roblox engineers to implement large parts of the user-facing application code as well as portions of the editor (Roblox Studio) as plugins. Roblox chose to open-source Luau to foster collaboration within the Roblox community as well as to allow other companies and communities to benefit from the ongoing language and runtime innovation. As a consequence, Luau is now also used by games like Alan Wake 2 and Warframe.

Our main [luau repository](https://github.com/luau-lang/luau) hosts source code for the language implementation and associated tooling. It is updated weekly with code updates from internal repository as well as binary releases, and welcomes [contributions](https://github.com/luau-lang/luau/blob/master/CONTRIBUTING.md). It should also be used for [questions or discussions](https://github.com/luau-lang/luau/discussions) or for [filing bug reports](https://github.com/luau-lang/luau/issues).

We also have other repositories that host satellite materials:

- [site repository](https://github.com/luau-lang/site) hosts documentation for the language and is available at https://luau.org/; pull requests improving documentation are always welcome!
- [rfcs repository](https://github.com/luau-lang/rfcs) hosts language and library proposals and is the way to discuss language evolution. The RFC process is [documented in the repository's README](https://github.com/luau-lang/rfcs/blob/master/README.md).
- [research repository](https://github.com/luau-lang/research) hosts academic white papers that we've published relating to Luau goals and implementation. You might also be interested in [a machine verified implementation of a subset of the type system](https://github.com/luau-lang/agda-typeck).
