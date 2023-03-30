#dgim

##description

#### This is the implementation of dgim algorithm in python where a stream of 32 bit is sliding over one's and zeroes converted from a text. here the letters in the text are converted into ascii values neglecting the numerical and special character if the ascii number is odd it's value is converted into 1 else the bit is zero. here we consider time stamp, buckets,count to caluculate the ones. intially the timestamp is zero, time stamp is updated when new bit comes. if the new bit is zero the buckets(it is in 2^0,2^1,2^2,2^3... size from right to left and in a stream each size of the bucket should be maximum of two) are not updated. if 1 added to the stream the window already have two bucket's of size 1 the two one's are merged this process continues untill not more than bucket's of two of each size are present.

##requirments

####python 3.7,google coolab

##visual studio

####pycharm

