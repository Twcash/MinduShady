# MinduShady

A Fragment shader editor purpose-built for Mindustry shaders.



Slightly more picky than what base-game is. You cannot multiply Int's and Floats.

Simply just cast the Int's to a Float instead or add .0 to any Int.



Full uniform detection and easy modification. You can import images with sampler 2d', modify float uniforms in real time, And u\_time incrementally updates (Of course it's the same 60 ticks/s timeframe). (almost)



Any Mindustry shader can be imported and work with no issue.



Quick tip.
Some shaders require a vec2 resolution (arkycite.frag and cryofluid.frag). You must manually set this resolution in the uniforms panel.



This does not contain:
- Many uniform types. (Feel free to suggest some in issues).

* &nbsp;A tutorial. I expect you to know how to make shaders.
* Flawless WebGl port as this was a nightmare.
* Saving shaders.
* Support for vertex shaders.
* To be bugless. (Feel free to address these in the issues. I would love to fix them.)



And yes. I use this tool.

