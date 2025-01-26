# C# Hello World Example

This repository contains a minimal "Hello, World!" implementation in C#, using the classic C# 1.0 style for maximum compatibility across all .NET versions. The implementation demonstrates the traditional structure of a C# program while maintaining simplicity.

## Purpose

The primary goals of this repository are:

1. Demonstrate the minimal code required to write and run a C# program
2. Serve as a basic test for .NET development environments
3. Provide a starting point for learning and experimentation

## Building and Running

### Windows

Using the .NET SDK:
```cmd
# Compile with C# compiler
csc Program.cs

# Run the compiled program
Program.exe
```

### Linux/macOS

Using the .NET SDK:
```bash
# Compile with C# compiler
csc Program.cs

# Run the compiled program
./Program
```

## Modern Implementation

If you're using C# 9.0 or later, you can use this more concise implementation using top-level statements:

```csharp
// Top-level statements eliminate the need for explicit program structure
Console.WriteLine("Hello, World!");
```

This modern syntax removes the ceremonial code (namespace, class, and Main method) while preserving the essential functionality. However, the traditional implementation in Program.cs provides better compatibility across all .NET versions.

## Contributing

While this repository aims to maintain minimalism, bug fixes and improvements to documentation are welcome. Please ensure any changes maintain the simplicity of the example.
