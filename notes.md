https://docs.julialang.org/en/v1/manual/getting-started/
-> Install Julia on Windows 10
  -> https://julialang.org/downloads/platform.html
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.0.5 (2019-09-09)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia> 1+1
2

julia> ans
2

julia>
help?>
search: ⊻ ⊋ ⊊ ⊉ ⊈ ⊇ ⊆ ≥ ≤ ≢ ≡ ≠ ≉ ≈ ∪ ∩ ∛ √ ∘ ∌ ∋ ∉ ∈ ℯ π ÷ ~ | ^ \ > < : / - + * & % ! if do IO |> rm pi mv in im fd cp cd GC >> >= >: => == <= << <: // != try let for end isa Ref Ptr Int Any === zip xor vec

  Welcome to Julia 1.0.5. The full manual is available at

  https://docs.julialang.org/

  as well as many great tutorials and learning resources:

  https://julialang.org/learning/

  For help on a specific function or macro, type ? followed by its name, e.g. ?cos, or ?@time, and press enter. Type ; to enter shell mode, ] to enter package mode.

julia>

-> Variables in Julia : https://docs.julialang.org/en/v1/manual/variables/
  -> Styling : https://docs.julialang.org/en/v1/manual/style-guide/#Style-Guide-1
    While Julia imposes few restrictions on valid names, it has become useful to adopt the following conventions:

Names of variables are in lower case.
Word separation can be indicated by underscores ('_'), but use of underscores is discouraged unless the name would be hard to read otherwise.
Names of Types and Modules begin with a capital letter and word separation is shown with upper camel case instead of underscores.
Names of functions and macros are in lower case, without underscores.
Functions that write to their arguments have names that end in !. These are sometimes called "mutating" or "in-place" functions because they are intended to produce changes in their arguments after the function is called, not just return a value.
