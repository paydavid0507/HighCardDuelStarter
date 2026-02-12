# High Card Duel (Starter)

## Run
1. Open `HighCardDuelStarter.sln` in Visual Studio 2022+
2. Restore NuGet packages (CommunityToolkit.Mvvm)
3. Run

## What students must implement/verify
- MVVM with CommunityToolkit:
  - `[ObservableProperty]` and `[RelayCommand]`
- Repository pattern:
  - `IGameSessionRepository` + `InMemoryGameSessionRepository`
- In-memory only (no files/DB)
- Buttons:
  - Draw Turn: generates 2 random cards, updates score, leader, history
  - Reset: clears everything

## Notes
- The starter already includes a working basic implementation for DrawTurn.
- For the exam, you can comment out the DrawTurn body and ask students to implement it.
