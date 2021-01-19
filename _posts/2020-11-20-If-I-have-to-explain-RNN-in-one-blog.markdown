==Fist== What?

RNN is different type of structure of Neural Network, they designed it like that just to make use of sequence learning .

++So what is the differnt, why not use simple RNN ? ++
+ Input size and outputsize stay fixed, even u can padding it, its doesn seem to make any representation about it
-> handle??

+ Share learning ??




#implement note


AT TIME STEP T, each cell

Input X (m, nx)
hiddenstate (m,na)
=> (m, nx) * (nx, na)  =(m, na) (1)



Previous A (m, na)
hiddenstate (m, na)
=> (m,na) *  (na, na) = (m, na) (2)

(1) + (2) + ba -> (m, na)


Output y (m, ny)
hiddenstate (m, na)
=> (m, na) *  (na, ny)    = (m, ny)



#notes on foward : theo keras, way = 0, nhung phan backprop thi ko thay cap nhat way?
                    


###implement backprop base on https://towardsdatascience.com/back-to-basics-deriving-back-propagation-on-simple-rnn-lstm-feat-aidan-gomez-c7f286ba973d

#notes on building RNN step by step coursera -> + ko co dao ham layer cuoi theo Loss
                                                + tai sao lai dao ham bien X theo Hidden state (a)?
                                                + co dX va` da0 trong dao. ham (tuy nhien khong cap nhat?)
                                                + chi cap nhat dWax, dWaa, dba 
                                                + 