# Flame-the-Guard
An online platform for a two-person card game.  
(Age: 8 or above)  

Play Here:
Flame-the-Guard.github.io  



How to Play:  

1. Setup: Each player starts with 10 fire barriers. The board has 5 positions; each player may stack up to 2 main cards per position.  

2. Each round: Both players draw to 5 main cards, then place 1 card face-down on any position. Player 1 goes first on odd rounds, Player 2 on even rounds.  

3. Flip: Both cards are revealed. If they land on the same position, a face-off is triggered there. If not, no face-off is triggered at that position.

4. Face-off (simultaneous): Compare each card's ⚔ ATK against the other's 🛡 RES. 
      ATK < RES → absorbed, nothing happens.
      ATK = RES → defender destroyed, 0 fire barriers lost.
      ATK > RES → defender destroyed, defender loses (ATK − RES) fire barriers.  

5. After the face-off, or if no face-off is triggered, players draw up to five cards, then proceed to round 2.  

6. In round 2 and subsequent rounds, players run these phases in order after flipping their cards:  
       Protection: Each Construction worker gives +1 draw, each Scientist gives +2. Attach draws to any of your non-Fire cards to add 🛡 RES.  
       Arsonist: Each Arsonist lets you remove 1 opponent protection card.  
       Swap: Discard 1+ board cards and replace with hand cards whose 💰 currency is equal or greater. Max 2 cards per position.  

7. Binding peptide rule: CsgA and BslA can only be attached to a card that already has a Binding peptide. Burning the last peptide discards all CsgA/BslA on that card too.  

8. Protection disposal: When a main card leaves the board (destroyed or swapped off), its protection cards are discarded with it.  

9. Round 1 is special: Only Draw → Place → Flip → Face-off. No protection, arsonist, or swap phases.

10. Win: You lose if your fire barriers hit 0.

11. Deck exhaustion: If either deck can't supply enough cards for both players' draws in a round, the game ends immediately. More fire barriers = winner (tie = draw).  



Created by ZXE  
Original game design by CTLCass, CWMan
