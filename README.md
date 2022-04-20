# study-java





Чтение/запись:

https://docs.oracle.com/javase/8/docs/api/java/io/BufferedReader.html
https://docs.oracle.com/javase/8/docs/api/java/util/Scanner.html



Scanner scan = new Scanner(System.in);

List<Integer> lst = new ArrayList<Integer>();

while (scan.hasNextInt())
{
    lst.add(scan.nextInt());
}
scan.close();

for(int l : lst)
{
    System.out.println(l);
}


