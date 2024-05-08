LIN3046 Group Report: Female Discourse Research
===========================

### Introduction

a. Descriptive Data
b. Research Question(s) or problem addressed

# Table of Contents

- [Dataset](#dataset)
    - [Transcription](#transcription)
    - [Segmentation](#Segmentation)
    - [Metadata](#Metadata)
    - [Annotation](#Annotation)
- [Methodology](#Methodology)
    - [Collection](#collection)
    - [Cleaning](#cleaning)
    - [Analysis](#analysis)
- [Discussion](#discussion)
- [Contributors](#contributors)

# Dataset

Here should describe our basic idea of dataset. Introduce this part will contain those items:
a. Transcription(Audio only) b. Segmentation c. Metadata d. Annotation

## Transcription

Here should be put our original transcrption (complete text or just an excerpt as an example???) 

## Segmentation

I’m not sure what this part actually contain?? Talk about how we cut the original transcript??

## Metadata

Metadata is 'data about data', which means a structured data excerpted from the information resource and be used to describe its characteristics and content. It is used to organize, describe, retrieve, preserve and manage information and knowledge resources.

Therefore, what is the metadata for our collected data? --->
? The general information about the youtuber we colleted ?? which type of youtuber? her video style/ vibe (may influence the discourse feature)? 


# Methodology


## Assets

```
111

```

## Assets (alternative)

```
Assets
+---Art
|   +---Materials
|   +---Models      # FBX and BLEND files
|   +---Music
|   +---Prefabs
|   +---Sound       # Samples and sound effects
|   +---Textures
|   +---UI
+---Levels          # Unity scene files
+---Src             # C# scripts and shaders
|   +---Framework
|   \---Shaders
```

## Scripts

Use namespaces that match your directory structure.

A Framework directory is great for having code that can be reused across projects.

The Scripts folder varies depending on the project, however, `Environment`, `Framework`, `Tools` and `UI` should be consistent  across projects.

```
Scripts
+---Environment
+---Framework
+---NPC
+---Player
+---Tools
\---UI
```

## Models

Separate files from the modelling program and ready to use, exported models.

```
Models
+---Blend
\---FBX
```

# Workflow

## Models

File extension: `FBX`

Even though Unity supports Blender files by default, it is better to keep what is being worked on and what is a complete, exported model separate. This is also a must when using other software, such as Substance for texturing.

Use `Y up`, `-Z forward` and `uniform scale` when exporting.

## Textures

File extension: `PNG`, `TIFF` or `HDR`

Choose either a `Specularity/Glossiness` or `Roughness/Metallic` workflow. This depends on the software being used and what your artists are more comfortable with. Specularity maps have the advantage of being having the possibility to be RGB maps instead of grayscale (useful for tinted metals), apart from that there is little difference between the result from either workflow.

### Texture Suffixes

Suffix | Texture
:------|:-----------------
`_AL`  | Albedo
`_SP`  | Specular
`_R`   | Roughness
`_MT`  | Metallic
`_GL`  | Glossiness
`_N`   | Normal
`_H`   | Height
`_DP`  | Displacement
`_EM`  | Emission
`_AO`  | Ambient Occlusion
`_M`   | Mask

### RGB Masks

It is good practice to use a single texture to combine black and white masks in a single texture split by each RGB channel. Using this, most textures should have:

```
texture_AL.png  # Albedo
texture_N.png   # Normal Map
texture_M.png   # Mask
```

Channel | Spec/Gloss        | Rough/Metal
:-------|:------------------|:-----------
R       | Specularity       | Roughness
G       | Glossiness        | Metallic
B       | Ambient Occlusion | Ambient Occlusion

#### The blue channel can vary depending on the type of material:

 - For character materials use the `B` channel for *subsurface opacity/strength*
 - For anisotropic materials use the `B` channel for the *anisotropic direction map*

## Configuration Files

File extension: `INI`

Fast and easy to parse, clean and easy to tweak.

`XML`, `JSON`, and `YAML` are also good alternatives, pick one and be consistent.

Use binary file formats for files that should not be changed by the player. For multiplayer games store configuration data on a secure server.

## Localization

File extension: `CSV`

Widely used by localization software, makes it trivial to edit strings using spreadsheets.

## Audio

File extension: `WAV` while mixing, `OGG` in game.

Preload small sound clips to memory, load on the fly for longer music and less frequent ambient noise files.

# Be Consistent

> The point of having style guidelines is to have a common vocabulary of coding so people can concentrate on what you're saying rather than on how you're saying it. We present global style rules here so people know the vocabulary, but local style is also important. If code you add to a file looks drastically different from the existing code around it, it throws readers out of their rhythm when they go to read it. Avoid this.

-- [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html)

---
