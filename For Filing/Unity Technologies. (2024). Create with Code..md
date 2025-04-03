https://learn.unity.com/course/create-with-code/?tab=overview&uv=6

# Course Introduction

## 1. Welcome

- Practical course to program anything
- For many popular formats
- Code in C#

## 2. Watch, then Do

- Watch then do to practice most the concepts taught throughout the course

# Unit 1 Introduction

- Create driving simulator prototype
- Learn player control objects
- Take inputs of controller
- Translate it to action

# Lesson 1.1 - Start your 3D Engines

- Assets can be imported as a whole package to include all related items
- Navigating the scene view can be done by holding right click to go into a fps control style with wasd. E and Q Peds up or down. Holding alt allows orbital rotation with left click drag, or zoom with right click drag.
- While and object is highlighted in the hierarchy window, pressing F focuses the object in the scene
- assets can be inserted into scenes by dragging into scene or hierarchy
- 1 unit in unity is 1 meter
- Game view is a preview of the game from the camera, and can be started with the play buttons at the top. Any that changes that occur in the preview mode is reset to inital settings when stopped

# Lesson 1.2 - Start your 3D Engines

- Scripts are instructions for objects in unity
- Script files can be dragged onto objects
- Mono script is the default script the tutorial mentions
- Capitalize each letter of the name, and leave no spaces to follow standard naming convention
- IDE is an Integrated Development Environment, and can be any other software, but free stock is Microsoft Visual Studio

```
using UnityEngine;

public class PlayerController2 : MonoBehaviour
{
    // Start is called once before the first execution of Update after the MonoBehaviour is created
    void Start()
    {
        
    }

    // Update is called once per frame
    void Update()
    {
        
    }
}
```

```
public class PlayerController2 : MonoBehaviour
```

- Blue words in C# are common keywords
- ":" means that the preceding word inherits from the following class from MonoBehavior
- // is notation for a comment
- Default programming language is C#, but there are many other languages that can work such as C++
- t and T is big in transform. t refers to the object's component in the 

```
transform.Translate()
```

- Methods can be ended with a ; to indicate the end of the instruction
- Another method can be Vector3 that uses more language based coding

```
transform.Translate(Vector3.forward);
```

- Math can be done within methods

```
Time.DeltaTime
```

- counts seconds 

# Lesson 1.3 - Start your 3D Engines

