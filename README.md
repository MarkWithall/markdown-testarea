# markdown-testarea

## Without paragraph breaks

1. Top level
  1. Second level
    1. Third level
  2. Second level

## With paragraph breaks

1. Top level

  1. Second level

    1. Third level

  2. Second level

## Code Highlighting Test

```csharp
public class Test
{
    public Test()
    {
    }
    
    public override string ToString()
    {
        return base.ToString();
    }
}
```

```diff
     game_moves = [0, 3, 1, 5, 2]
      player = last_player(game_moves)
      player_moves = moves_for_player(player, game_moves)
 -    assert is_win(player_moves) is False
 +    assert is_win(player_moves) is True
  
  
  def is_legal(move, moves_played):
```
