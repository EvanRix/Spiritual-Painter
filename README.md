# Spiritual-Painter

## Introduction

Spiritual-Painter(SP) is a platform game that consists of 4 levels in total.
The game is greatly inspired by Splatoon, a phenomenous multiplayer game released by Nintendo. Plus, the game difficulty is supper challenging, so get yourself prepared before starting to play it!!

## Platform

Framework: Unreal Engine
Version: 4.27.2

## Coding Style

- The first letter of each word in a name (such as type name or variable name) is capitalized, and there is usually no underscore between words. For example, `Health` and `UPrimitiveComponent` are correct, but not `lastMouseCoordinates` or `delta_coordinates`.
- Type names are prefixed with an additional upper-case letter to distinguish them from variable names. For example, `FSkin` is a type name, and `Skin` is an instance of a `FSkin`.
  - Template classes are prefixed by T.
  - Classes that inherit from `UObject` are prefixed by U.
  - Classes that inherit from `AActor` are prefixed by A.
  - Classes that inherit from `SWidget` are prefixed by S.
  - Classes that are abstract interfaces are prefixed by I.
  - Enums are prefixed by E.
  - Boolean variables must be prefixed by b (for example, `bPendingDestruction`, or `bHasFadedIn`).
  - Most other classes are prefixed by F, though some subsystems use other letters.







reference：https://docs.unrealengine.com/4.27/en-US/ProductionPipelines/DevelopmentSetup/CodingStandard/


## Contributors

<a href="https://github.com/jasonyxwu/Spiritual-Painter/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jasonyxwu/Spiritual-Painter" />
</a>

