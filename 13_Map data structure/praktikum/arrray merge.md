
package task13.array;
import java.util. * ;
public class merge {
    public static void main(String args[]) {
        String str1[] = {
                "lee",
                "jin",
        };
        String str2[] = {
                "kazuya",
                "panda",
        };
        System.out.print("Array pertama:");
        for (int i = 0; i < str1.length; i++) {
            System.out.print(" " + str1[i]);
        }
        System.out.print("\nArray kedua:");
        for (int i = 0; i < str2.length; i++) {
            System.out.print(" " + str2[i]);
        }
        List list = new ArrayList(Arrays.asList(str1));
        list.addAll(Arrays.asList(str2));
        Object[] str3 = list.toArray();
        System.out.print("\nArray merge: ");
        System.out.println(Arrays.toString(str3));
    }
}
