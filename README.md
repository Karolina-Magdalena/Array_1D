# Array_1D

How to print out elements of array:

for (int i = 0; i < a.length; i++) {
            System.out.println(a[i]);
        }

How to write elements to array:

Scanner scan = new Scanner(System.in);
        int n = scan.nextInt();
        int[] a = new int[n];
        for (int i=0;i<n;i++) {
            int num = scan.nextInt();
            a[i]=num;
        }
        scan.close();
