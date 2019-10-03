XREF: https://www.broyhillasset.com/2017/09/11/algorithms-live-part-2-optimal-stopping/

There is a problem called the "optimal stopping problem". The basic version of it is that there is a stream of data coming in and you are trying to pick the best out of the entire set `S`. However, you are only given 1 element from `S` at a time. If you choose not to take the element, you lose it forever. If you choose to pick that element, you cannot pick another one and the choosing stops. The question is when should you stop?

If you stop too early, you risk not seeing if a later element is better than the one you've chosen

If you stop too late, you risk losing the best element by passing it over

According to the book "[Agorithms To Live By](http://algorithmstoliveby.com/)", the answer is about 36% of the limited resource in the situation. 

This script is to test this math using computerized simulations.

TODO
- actually write this script haha
