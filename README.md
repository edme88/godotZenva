# [Humble Bundle – Complete Godot 2025 – Tier 3](https://academy.zenva.com/course/humble-bundle-complete-godot-2025-tier-3/)

## [1. Intro to Godot 4 Game Development](https://academy.zenva.com/course/intro-to-godot-4-game-development-2023/)
Time: 2hs 44min
1. Course Requirements
2. Introduction
3. Downloading Godot 
4. Godot Installation and Version
5. Creating a New Project
6. Editor Overview
7. Quiz - Editor Overview 
8. Scene Navigation
9. Basic Shorcuts Cheatsheet
10. Importing Assets
11. Quiz - Navigation and Asset Importing
12. Nodes and Scenes - Part 1 
13. Nodes and Scenes - Part 2
14. Quiz - Nodes and Scenes
15. Node Toold - Part 1 
16. Node Toold - Part 2
17. Parenting
18. Quiz - Node Toold and Parenting 
19. Intro to 3D - Part 1
20. Intro to 3D - Part 2
21. Quiz - Intro to 3D
22. Materials - Part 1
23. Materials - Part 2
24. Lights
25. Quiz - 3D Visuals
26. Intro to Scripting
27. Variables - Part 1
28. Variables - Part 2
29. Variables - Part 3

Example:
```
extends Node2D

var country_name : String = "Argentina"
var population : int = 500000
var highest_altitude : float = 34.23
var landlocked : bool = true

# Called when the node enters the scene tree for the first time.
func _ready() -> void:
	print(country_name)
	print(population)
	print(highest_altitude)
	print(landlocked)
```

30. Variables - [In-depth Overview](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
31. Quiz - Variables 
32. Operators - Part 1
33. Operators - Part 2

Exercise:
```
extends Node2D

var score : int = 0

func _ready() -> void:
	score += 1
	print(score)
	score *= 10
	print(score)
	score -= 1
	print(score)
	score /= 3
	print(score)
```

34. Operators - [In-depth Overview](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_basics.html)
35. Quiz - Operators 
36. Conditions - Part 1
37. Conditions - Part 2
38. Conditions - Part 3
39. Conditions - In-depth Overview

```
extends Node2D

var score : int = 10

func _ready() -> void:
	if score == 10:
		print("You win")
  elif score  > 60:
    print("A")
  else:
    print("D")
```

40. Quiz - Conditions 
41. Functions - Part 1
42. Functions - Part 2
43. Functions - In-depth Overview

```
func _ready() -> void:
	var result = _add(3, 7)
	print(result)

func _add(a, b):
	var sum = a + b
	return sum
```

44. Quiz - Functions 
45. Vectors
46. Vectors - In-depth Overview

```
# Position or direction
extends Sprite2D

# Called when the node enters the scene tree for the first time.
func _ready() -> void:
	var vec = Vector2(500, -200)
	global_position = vec

var timer : float = 0.0

# Called every frame. 'delta' is the elapsed time since the previous frame.
func _process(delta: float) -> void:
	timer += 1.0 * delta
	print(timer)
	var direction = Vector2(1,1)
	global_position += direction * 30 * delta
```
47. Quiz - Vectors ✅
48. Challenge - Part 1
49. Challenge - Part 2
50. Coin Collector Game - Part 1
51. Coin Collector Game - Part 2
52. Coin Collector Game - Part 3
53. Coin Collector Game - Part 4
54. Coin Collector Game - Part 5
55. Player - In-depth Overview
56. Coin - In-depth Overview
57. Quiz - Coin Collector Project
58. Exporting Your Game
59. Setting a Custom Game Icon
60. Conclusion
61. Full Source Code - Godot Game Engine 

## [3. Git and GitHub for Godot – Version Control Essentials](https://academy.zenva.com/course/godot-version-control-course/)
Time: 48min
Certificado: https://academy.zenva.com/certificate/f215aa96612a
1. Course Requirements
2. Introduction
3. Godot installation and Version
4. Intro to GitHub
5. Creating a Repository
6. GitHub Desktop
7. Vonnecting a Godot Project
8. Making Changes to the Project
9. Adding Collaborators
10. Pulling from the Repo
11. Merge Conflicts
12. Conclusion


