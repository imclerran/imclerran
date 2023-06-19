<!-- ### [![Typing SVG][greeting_svg]][greeting_link] -->

### My name is Ian McLerran, and I'm glad you're here!

```haskell
{-- Welcome to my GitHub page. Feel free to browse around, and fork too if ya like! --}

main :: IO () 
main = putStrLn (hello "World") 

hello :: [Char] -> [Char]
hello who = 
    flip (++) who
    (foldr (:) [head (reverse (take 5 ['$','#'..]))] 
    ((foldr (:) (take 2 (repeat 'l') ++ 
    filter (> 'n') (take 3 ['m'..])) 
    (flip (:) [[' '..] !! 69] 
    (head (drop 7 (take 8 ['A'..'Z']))))) ++ 
    [(last (take 3 ['*'..]))]))
```

`💻 I'm currently working on:`<br>
[![Current project][project_badge]][project_link]
[![GitHub last commit][last_commit_badge]][project_link]
<br>
`✏️ Favorite languages:`
<br>
[![Haskell][haskell_badge]][haskell_link]
[![Dart][dart_badge]][dart_link]
[![C Sharp][csharp_badge]][csharp_link]
<br>
 `📚 I am learning:`
<br>
[![React][react_badge]][react_link]
[![PyTorch][pytorch_badge]][pytorch_link]
<br>
`🎮 Having fun with:`
<br>
[![Steam Deck][steamdeck_badge]][steamdeck_link]

```haskell
{-- Thanks for stopping by! Check out my resume below: --}
```

[![My Resume][resume_badge]][resume_link]


<!-- urls: -->
[greeting_svg]: https://readme-typing-svg.herokuapp.com?height=30&lines=%F0%9F%91%8B+Hi+there%2C+I'm+glad+you're+here!!
[greeting_link]: https://git.io/typing-svg
[project_badge]: https://img.shields.io/badge/Repo-Achiever%20App-orange?style=flat
[project_link]: https://github.com/imclerran/achiever_app
[last_commit_badge]: https://img.shields.io/github/last-commit/imclerran/projectile-inferno
[last_commit_link]: https://github.com/imclerran/projectile-inferno
[haskell_badge]: https://img.shields.io/badge/-Haskell-purple?logo=haskell
[haskell_link]: https://www.haskell.org
[dart_badge]: https://img.shields.io/badge/-Dart-blue?logo=dart
[dart_link]: https://dart.dev
[csharp_badge]: https://img.shields.io/badge/-C%20Sharp-009900?logo=csharp
[csharp_link]: https://docs.microsoft.com/en-us/dotnet/csharp/
[rust_badge]: https://img.shields.io/badge/-Rust-993300?logo=rust
[rust_link]: https://www.rust-lang.org
[llvm_badge]: https://img.shields.io/badge/-LLVM-8c8c8c?logo=llvm
[llvm_link]: https://llvm.org
[pytorch_badge]: https://img.shields.io/badge/-PyTorch-blueviolet?logo=pytorch
[pytorch_link]: https://pytorch.org
[react_badge]: https://img.shields.io/badge/-React-%2323272f?logo=react
[react_link]: https://react.dev
[steamdeck_badge]: https://img.shields.io/badge/-My%20Steam%20Deck!!!-darkblue?logo=steamdeck
[steamdeck_link]: https://steamdeck.com
[resume_badge]: https://img.shields.io/badge/Resume-Download-blue?style=for-the-badge&logo=adobeacrobatreader
<!--&link=https://www.dropbox.com/s/ylg918qc67kuype/Resume.pdf?dl=1-->
[resume_link]: https://www.dropbox.com/s/ylg918qc67kuype/Resume.pdf?dl=1

