# System Tips

A C# .NET 9.0 Windows Forms desktop application.

## Requirements

- .NET 9.0 SDK or later
- Windows OS (or EnableWindowsTargeting on non-Windows platforms)

## Building

```bash
dotnet build SystemTips.sln
```

## Running

```bash
dotnet run --project SystemTips/SystemTips.csproj
```

## Project Structure

- `SystemTips.sln` - Solution file
- `SystemTips/` - Main application project
  - `Program.cs` - Application entry point
  - `MainForm.cs` - Main application form
  - `MainForm.Designer.cs` - Form designer code
  - `MainForm.resx` - Form resources