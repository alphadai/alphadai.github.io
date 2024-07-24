# Overview

## Table of Contents

  - [AGI](#AGI)
    - [LLM](#LLM)
  - [Graphic](#Graphic)
    - [Vulkan](#Vulkan)
    - [Game Shader](#Game-Shader)
  - [Game AI](#Game-AI)
    - [Game Amimation](#Game-Amimation)
    - [Game Pathfind](#Game-Pathfind)
  - [Game play](#Game-play)
      - [ray casting](#ray-casting)
      - [Mesh processing](#Mesh-processing)
      - [Image process](#Image-process)
  - [C++](#C++-Library)
      - [Framework](#Framework)
      - [File system](#File-system)
      - [Standard template library](#Standard-template-library)
      - [design patterns](#design-patterns)
      - [log](#log)
      - [benchmark test](#benchmark-test)
      - [collection single header](#collection-single-header)
  - [Game engine](#Game-engine)
      - [3D game engine](#3D-game-engine)
  - [Released source code](#Released-source-code)
      - [Game Source code](#Game-Source-code)
  - [Misc](#Misc)
      - [AIGC](#AIGC)
      - [Web](#Web)
      - [Data analysis](#Data-analysis)
      - [reference](#reference)

---

## AGI
--------

#### LLM
* [OpenLLaMA](https://github.com/openlm-research/open_llama) - An open source reproduction of Meta’s LLaMA model, developed by Berkeley AI Research, this project provides permissively licensed models with 3B, 7B, and 13B parameters, and is trained on one trillion tokens
* [Falcon-Series](https://github.com/huggingface/blog/blob/main/falcon.md#the-falcon-models) - Falcon-Series consists of two models: Falcon-40B and Falcon-7B. The series has a unique training data pipeline that extracts content with deduplication and filtering from web data
* [MPT-Series](https://github.com/mosaicml/llm-foundry) - A set of decoder-only large language models, MPT-Series models have been trained on one trillion tokens spanning code, natural language text, and scientific text. Developed by MosaicML
* [FastChat-T5:](https://huggingface.co/lmsys/fastchat-t5-3b-v1.0) - A large transformer model with three billion parameters, FastChat-T5 is a chatbot model developed by the FastChat team through fine-tuning the Flan-T5-XL model. Trained on 70,000 user-shared conversations, it generates responses to user inputs autoregressively and is primarily for commercial applications. It’s a strong fit for applications that need language understanding, like virtual assistants, customer support systems, and interactive platforms. 

## Graphic
-------- 


#### Vulkan

* [Acid](https://github.com/alphafork/Acid) - Acid is an open-source, cross-platform game engine written in modern C++17 and structured to be fast, simple, and extremely modular.
* [awesome-vulkan](https://github.com/alphafork/awesome-vulkan) - A curated list of awesome Vulkan libraries, debuggers and resources
* [Vulkan Samples](https://github.com/khronosGroup/Vulkan-samples) - The Vulkan Samples is collection of resources to help you develop optimized Vulkan applications
*  [VulkanCapsViewer](https://github.com/alphafork/VulkanCapsViewer) - Client application to display hardware implementation details for GPUs supporting the new Vulkan(tm) API by Khronos.
*  [Vulkan Memory Allocator](https://github.com/alphafork/VulkanMemoryAllocator) - Easy to integrate Vulkan memory allocation library.

#### Game Shader

* [Shaderc](https://github.com/alphafork/shaderc) - A collection of tools, libraries and tests for shader compilation
* [awesome-glsl](https://github.com/alphafork/awesome-glsl) - best resources I have found in my way to learn how to program the amazing GLSL
* [3d-game-shaders-for-beginners](https://github.com/alphafork/3d-game-shaders-for-beginners) - Interested in adding textures, lighting, shadows, normal maps, glowing objects, ambient occlusion, and more to your 3D game
* [Unity Built in Shaders](https://github.com/alphafork/Unity-Built-in-Shaders) - An unofficial repo for Unity Built-in Shaders
 
---

## Game AI
--------

#### Game Amimation

* [ozz-animation](https://github.com/alphafork/ozz-animation) - open source c++ 3d skeletal animation library and toolset
* [openpose](https://github.com/alphafork/openpose) - OpenPose represents the first real-time multi-person system to jointly detect human body, hand, facial, and foot keypoints (in total 135 keypoints) on single images.

#### Game Pathfind

* [recastnavigation](https://github.com/alphafork/recastnavigation) - Recast is state of the art navigation mesh construction toolset for games.

---

## Game play
--------

#### ray casting

* [Embree](https://github.com/embree/embree) - Intel Corporation High Performance Ray Tracing Kernels
* [OptiX Toolkit](https://github.com/NVIDIA/optix-toolkit) - A set of utilities commonly used in applications utilizing the OptiX ray tracing API

#### Mesh processing

* [Mesh-processing-library](https://github.com/alphafork/Mesh-processing-library) - C++ library and programs that demonstrate mesh processing techniques in computer graphics published at ACM SIGGRAPH in 1992–1998:

#### Image process

* [PaddleClas](https://github.com/alphafork/PaddleClas-image-recognition-toolset) - PaddleClas is an image recognition toolset for industry and academia, helping users train better computer vision models and apply them in real scenarios.

---

## C++ Library
--------

#### Framework

* [Entitas](https://github.com/alphafork/Entitas-CSharp) - The Entity Component System Framework for C# and Unity

#### File system

* [PhysicsFS](https://github.com/alphafork/physfs) - PhysicsFS is a library to provide abstract access to various archives. It is intended for use in video games, and the design was somewhat inspired by Quake 3's file subsystem

#### Standard template library

* [EA Standard Template Library](https://github.com/alphafork/EASTL) - EASTL stands for Electronic Arts Standard Template Library. It is a C++ template library of containers, algorithms, and iterators useful for runtime and tool development across multiple platforms.
* [cppwinrt](https://github.com/alphafork/cppwinrt) - an entirely standard C++ language projection for Windows Runtime (WinRT) APIs, implemented as a header-file-based library, and designed to provide you with first-class access to the modern Windows API.
* [abseil-cpp](https://github.com/alphafork/abseil-cpp) - The repository contains the Abseil C++ library code. Abseil is an open-source collection of C++ code (compliant to C++14) designed to augment the C++ standard library..
* [folly](https://github.com/alphafork/folly) - Folly (acronymed loosely after Facebook Open Source Library) is a library of C++14 components designed with practicality and efficiency in mind.

#### design patterns

* [Guide-awesome-design-patterns](https://github.com/alphafork/Guide-awesome-design-patterns) - A curated list of software and architecture related design patterns.

#### log

* [spdlog](https://github.com/alphafork/spdlog) - Very fast, header-only/compiled, C++ logging library.


#### benchmark test
* [C++ Benchmarking Library](https://github.com/DigitalInBlue/Celero) - Once Celero is added to your project. You can create dedicated benchmark projects and source files.


#### collection single header

* [Single-header-file-libraries-collection](https://github.com/alphafork/Single-header-file-libraries-collection) 
* [cr](https://github.com/alphafork/cr) - A single file header-only live reload solution for C, written in C++

---


## Game engine
--------

#### 3D game engine

* [Acid](https://github.com/alphafork/Acid) - Acid is an open-source, cross-platform game engine written in modern C++17 and structured to be fast, simple, and extremely modular.
* [WickedEngine](https://github.com/alphafork/WickedEngine) - Wicked Engine is an open-source game engine written in C++. It is easy to use, high performance and feature rich.


## Released source code
--------

#### Game Source code

* [REDALERT](https://github.com/alphafork/Game_CnC_Remastered_Collection) - 红色警戒 and 泰伯利亚的黎明 source code


## Misc
--------

#### AIGC

* [chatbox](https://github.com/alphafork/AIGC-chatbox) - the Ultimate Copilot on Your Desktop. Chatbox is a desktop app for GPT-4 / GPT-3.5 (OpenAI API) that supports Windows, Mac & Linux.
* [OpenAI Cookbook](https://github.com/alphafork/openai-cookbook) - The OpenAI Cookbook shares example code for accomplishing common tasks with the OpenAI API

#### Web

* [Scrapy](https://github.com/alphafork/scrapy) - Scrapy is a fast high-level web crawling and web scraping framework, used to crawl websites and extract structured data from their pages

#### Data analysis

* [pandas](https://github.com/alphafork/pandas) - pandas is a Python package that provides fast, flexible, and expressive data structures designed to make working with "relational" or "labeled" data both easy and intuitive. It aims to be the fundamental high-level building block for doing practical, real world data analysis in Python. Additionally, it has the broader goal of becoming the most powerful and flexible open source data analysis / manipulation tool available in any language. It is already well on its way towards this goal.

#### reference

* [Best-websites-a-programmer-should-visit](https://github.com/alphafork/Best-websites-a-programmer-should-visit) - Some useful websites for programmers.
* [build-your-own-x](https://github.com/alphafork/build-your-own-x) - misc reference 
* [GameDevMind](https://github.com/alphafork/GameDevMind) - 游戏开发技术图谱


