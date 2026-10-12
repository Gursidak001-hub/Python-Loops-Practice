.. code:: ipython3

    #Q1. Print numbers from 1 to 10.
    for i in range(1,11,1):
     print(i)
    
    


.. parsed-literal::

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    

.. code:: ipython3

    #Q2. Print numbers from 1 to n, where n is entered by the user.
    
    n=int(input("Enter a Number"))
    for i in range(1,n+1,1):
          print(i)
    
    
    
    


.. parsed-literal::

    Enter a Number 5
    

.. parsed-literal::

    1
    2
    3
    4
    5
    

.. code:: ipython3

    #Q3. Print all even numbers from 0 to n.
    
    n=int(input("Enter a Number"))
    for i in range(2,n+1,2):
        print(i)
    
    
    
    


.. parsed-literal::

    Enter a Number 5
    

.. parsed-literal::

    2
    4
    

.. code:: ipython3

    #Q4. Print all odd numbers from 1 to n.
    
    n=int(input("Enter a Number"))
    for i in range(1,n+1,2):
        print(i)
    
    
    


.. parsed-literal::

    Enter a Number 6
    

.. parsed-literal::

    1
    3
    5
    

.. code:: ipython3

    #Q5. Print numbers from n down to 1.
    
    n=int(input("Enter a Number"))
    for i in range(n,0,-1):
        print(i)
    
    


.. parsed-literal::

    Enter a Number 10
    

.. parsed-literal::

    10
    9
    8
    7
    6
    5
    4
    3
    2
    1
    

.. code:: ipython3

    #Q6. Print the multiplication table of a number.
    
    n=int(input("Enter a Number"))
    for i in range(1,11,1):
        print(n, "x", i, "=", n * i)
    
    
    
    


.. parsed-literal::

    Enter a Number 3
    

.. parsed-literal::

    3 x 1 = 3
    3 x 2 = 6
    3 x 3 = 9
    3 x 4 = 12
    3 x 5 = 15
    3 x 6 = 18
    3 x 7 = 21
    3 x 8 = 24
    3 x 9 = 27
    3 x 10 = 30
    

.. code:: ipython3

    #Q7. Calculate the sum of numbers from 1 to n.
    
    n=int(input("Enter a Number"))
    ntotal=0
    for i in range(1,n+1,1):
        ntotal=ntotal+i
        print("sum = ",ntotal)
    
    
    


.. parsed-literal::

    Enter a Number 5
    

.. parsed-literal::

    sum =  1
    sum =  3
    sum =  6
    sum =  10
    sum =  15
    

.. code:: ipython3

    #Q8. Print the square of every number from 1 to n.
    
    n=int(input("Enter a Number"))
    for i in range(1,n+1,1):
    
        print("Square value = ",i*i)
    
    


.. parsed-literal::

    Enter a Number 5
    

.. parsed-literal::

    Square value =  1
    Square value =  4
    Square value =  9
    Square value =  16
    Square value =  25
    

.. code:: ipython3

    # Q9. Count how many numbers from 1 to n are divisible by 3.
    
    n=int(input("Enter a Number"))
    for i in range(1,n+1,1):
    
        print(i%3==0)
    
    
    


.. parsed-literal::

    Enter a Number 5
    

.. parsed-literal::

    False
    False
    True
    False
    False
    

.. code:: ipython3

    #Q10. Print the word 'Python' five times using a loop.
    
    for i in range(0,5,1):
        print("Python")
    


.. parsed-literal::

    Python
    Python
    Python
    Python
    Python
    

.. code:: ipython3

    #Q11 count no of sales > 300
    Sales = [100, 200, 400, 500, 600, 300, 100, 300, 400, 500]
    count=0
    for i in range(0,len(Sales),1):
     if (Sales[i]>300):
         count=count+1
    print(count)     
    


.. parsed-literal::

    5
    

.. code:: ipython3

    #Q12 Count how many students passed or failed (>= 40)
    Marks = [10, 30, 50, 70, 80, 98, 76, 56, 78, 45, 67, 67, 89]
    count1=0
    count2=0
    for i in range(0,len(Marks),1):
       if(Marks[i]>=40):
           count1=count1+1
       else:
           count2=count2+1
    print("Number of students Pass:", count1)
    print("Number of students Fail:", count2)
    


.. parsed-literal::

    Number of students Pass: 11
    Number of students Fail: 2
    

.. code:: ipython3

    #Q13. Count the items whose quantity is finished (quantity ≤ 0)
    qty = (10, 30, 0, -7, 87, 45, 0, 56, 0, 45, -4)
    count=0
    for i in range(0,len(qty),1):
      if (qty[i]<=0):
        count=count+1
    print("The Finished qty is ", count)    


.. parsed-literal::

    The Finished qty is  5
    

