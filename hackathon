import java.util.LinkedList;
import java.util.List;

public class Main {

    public static void main(String[] argv)
    {
        List<Integer> r;
        System.out.println(r = team78(28753)); //28753 is our first number in the challenge.
        System.out.printf("Person %d is last\n", r.get(r.size() - 1));
    }

    static List<Integer> team78(int N)
    {
        if (N < 1 ) return null;

        List<Integer> p = new LinkedList<>();
        for (int i = 0; i < N; i++)
            p.add(i+1);

        List<Integer> r = new LinkedList<>();
        int i = (-1) % N;
        System.out.println("i= " + i);

        for (int j = N; j > 0; j--) {
            i = (i + 2) % N--;
            r.add(p.remove(i--));
        }

        return r;
    }
}
