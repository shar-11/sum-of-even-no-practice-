# sum-of-even-no-practice-
   Int number = 0;
     int sumOfEvenDigits = 0;
     Scanner scan =  new Scanner(System.in)
     System.out.print("Enter an integer number:: ");
     number = scan.nextInt();

     
     sumOfEvenDigits = findEvenDigitSum(number);

   
     System.out.println("The sum of even digits of"+
       " the number "+number+" = "+ sumOfEvenDigits);
     scan.close();
  }
