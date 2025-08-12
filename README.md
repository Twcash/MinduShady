# A fragment shader editor purpose-built for Mindustry shaders.

# 

# It’s slightly more picky than the base game: you cannot multiply Ints and Floats directly.

# Simply cast Ints to Float or add .0 to any Int.

# 

# Features full uniform detection and easy modification. You can import images with sampler2D, modify float uniforms in real time, and u\_time updates incrementally (at roughly 60 ticks per second).

# 

# Any Mindustry shader can be imported and will work with no issues.

# 

# Quick tip: Some shaders require a vec2 resolution (like arkycite.frag and cryofluid.frag). You must manually set this resolution in the uniforms panel.

# 

# This does not contain:

# 

* # Many uniform types (feel free to suggest some in issues).

# 

* # A tutorial — I expect you to know how to make shaders.

# 

* # A flawless WebGL port — this was a nightmare.

# 

* # Saving shaders.

# 

* # Support for vertex shaders.

# 

* # Bug-free operation (please report issues; I’d love to fix them).

# 

# And yes, I use this tool myself.

