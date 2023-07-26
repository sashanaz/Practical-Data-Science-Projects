Name: Sasha Nazareth
Student ID: 3912063

Instructions to execute the script files:

1. The code will run uptil 150 line using Run cells.

2. To plot the decision tree online, first run the 148th line. 
   Then go to Jupyter notebooks home page and open the file "tree.dot". 
3. Copy the code given in tree.dot. 
 The code is-

digraph Tree {
node [shape=box] ;
0 [label="Time <= 73.5\ngini = 0.451\nsamples = 239\nvalue = [157, 82]"] ;
1 [label="Age <= 73.5\ngini = 0.264\nsamples = 64\nvalue = [10, 54]"] ;
0 -> 1 [labeldistance=2.5, labelangle=45, headlabel="True"] ;
2 [label="Creatinine phosphokinase <= 87.0\ngini = 0.335\nsamples = 47\nvalue = [10, 37]"] ;
1 -> 2 ;
3 [label="gini = 0.5\nsamples = 8\nvalue = [4, 4]"] ;
2 -> 3 ;
4 [label="gini = 0.26\nsamples = 39\nvalue = [6, 33]"] ;
2 -> 4 ;
5 [label="gini = 0.0\nsamples = 17\nvalue = [0, 17]"] ;
1 -> 5 ;
6 [label="Time <= 199.0\ngini = 0.269\nsamples = 175\nvalue = [147, 28]"] ;
0 -> 6 [labeldistance=2.5, labelangle=-45, headlabel="False"] ;
7 [label="Time <= 124.5\ngini = 0.341\nsamples = 110\nvalue = [86, 24]"] ;
6 -> 7 ;
8 [label="gini = 0.233\nsamples = 67\nvalue = [58, 9]"] ;
7 -> 8 ;
9 [label="gini = 0.454\nsamples = 43\nvalue = [28, 15]"] ;
7 -> 9 ;
10 [label="Creatinine phosphokinase <= 1192.0\ngini = 0.116\nsamples = 65\nvalue = [61, 4]"] ;
6 -> 10 ;
11 [label="gini = 0.064\nsamples = 60\nvalue = [58, 2]"] ;
10 -> 11 ;
12 [label="gini = 0.48\nsamples = 5\nvalue = [3, 2]"] ;
10 -> 12 ;
}

4. Copy the above code in the given link- https://dreampuf.github.io/GraphvizOnline
5. After running the code, the decision tree will be seen. 
