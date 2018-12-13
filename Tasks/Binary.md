public class Binary {
    public static void main(String[] args)throws Exception {
        BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
        System.out.println("Введите число в дипазоне от 0 до 255");
        int x = Integer.parseInt(reader.readLine());
        if (x >= 0 && x <= 255){

            System.out.println("Ваше число в двоичном представлении - " + Integer.toBinaryString(x));
            return;
        }
        else{
            System.out.println("Вы ввели чисто не в том диапазоне, попробуйте снова");
        }
        System.out.println("Если хотите попробовать снова нажмите - y");

        String next = reader.readLine();
        
        if (next.equals("y")){
                               //что прописать здесь?
        }
        else {
            return;
        }
    }
}