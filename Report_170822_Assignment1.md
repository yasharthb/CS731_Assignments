                                                 Report: Blockchain Assignment 1

In the process of doing the assignment **I was able to implement both the 'txn_t::validate()' and the 'block_t::validate()' using self written 
my_validate_block_helper()**.I did a minor change in txn_t::update_balances() where I replaced 'balances[source_addr] = 0' with 'balances.erase(source_addr)' which otherwise was resulting in exceeded RAM in 6th Test Case.

My code implementation **passes all the 6 test cases.**

I did not violate any honor code to do this assignment. All the code is written by me only.


Yasharth Bajpai
170822