# StepsToMilesCalculator

A full-featured ASP.NET Core Razor Pages web application for converting steps to miles/kilometers, including:

- Custom stride, pace, height, and gender adjustments
- Steps-per-mile tables by height/gender
- Methodology and FAQ sections
- Responsive, accessible layout

## How to run

1. Clone this repo:
   ```
   git clone https://github.com/BijayPudipeddi/StepsToMilesCalculator.git
   cd StepsToMilesCalculator
   ```
2. Restore and run:
   ```
   dotnet restore
   dotnet run
   ```
3. Open [http://localhost:5000](http://localhost:5000) in your browser.

---

## Project Structure

- `Pages/` — Razor Pages (Calculator, Tables, Methodology, FAQ)
- `Models/` — Calculation logic
- `wwwroot/css/` — Styling
- `Program.cs` — App entry point
- `StepsToMilesCalculator.csproj` — Project config

---

## License

MIT