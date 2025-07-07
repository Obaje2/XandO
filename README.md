# XandO
package XandO;

import java.util.ArrayList;

public class Player {
    private String symbol;
    private ArrayList<Integer> moves = new ArrayList<>();

    public Player(String symbol) {
        this.symbol = symbol;
    }

    public String getSymbol() {
        return symbol;
    }

    public void addMove(int move) {
        moves.add(move);
    }

    public ArrayList<Integer> getMoves() {
        return moves;
    }

    public void clear() {
        moves.clear();
    }
}
