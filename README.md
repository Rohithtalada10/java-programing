 import java.util.ArrayList;
import java.util.List;

class John{
    public static void main(String[] args) {
        
        List<Integer> c = new ArrayList<Integer>();
        c.add(15);
        c.add(5);
        c.add(20);
        c.add(18);

        for(Object i :c){
            int num = (Integer) i;
            System.out.println(num);
        }     
    }
}
