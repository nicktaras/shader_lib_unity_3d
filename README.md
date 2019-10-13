# shader_lib_unity_3d
A Library of Shaders made for Unity 3D

This is an experimental project to learn more about the power of shaders.

Resources:
https://docs.unity3d.com/Manual/ShadersOverview.html

Base construct of a shader, regardless of its type.

`
Shader "MyShader" {
    Properties {
        _MyTexture ("My Texture", 2D) = "white" { }
        // Place other properties like colors or vectors here as well
    }
    SubShader {
        // here goes your
        // - Surface Shader or
        // - Vertex and Fragment Shader or
        // - Fixed Function Shader
    }
    SubShader {
        // Place a simpler "fallback" version of the SubShader above
        // that can run on older graphics cards here
    }
}
`
