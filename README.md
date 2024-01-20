# riceBags
Amazon Code Question - riceBags

You are shopping on Amazon.com for some bags of rice. Each listing displays the number of grains of rice that the bag contains. You want to buy a perfect set of rice bags from the entire search results list, riceBags. A perfect set of rice bags, perfect, is defined as:
• The set contains at least two bags of rice.
• When the rice bags in the set perfect are sorted in increasing order by grain count, it satisfies the condition perfectli] • perfect[i] = perfect]i+1] for all 1 ≤i< n. Here n is the size of the set and perfectli] is the number of rice grains in bag i.
Find the largest possible set perfect and return an integer, the size of that set. If no such set is possible, then return -1. It is guaranteed that all elements in riceBags are distinct.
Example
perfect sets.
Let the bags of rice available on Amazon have grain counts [3, 9, 4, 2, 16]. The following are the
• Set perfect = [B, 9]. The size of this set is 2.
• Set perfect = [4, 2]. The size of this set is 2.
• Set perfect = [4, 16]. The size of this set is 2.
• Set perfect = [4, 2. 16]. The size of this set is 3.
The size of the largest set is 3. The image below illustrates the correct ordering of the purchased rice bags by grains of rice.


Function Description
Complete the function maxSetSize in the editor below.
maxsetSize has the following parameter:
int riceBags(n]: the list of bags of rice by rice grain count
Returns
int: the size of the largest set possible or -1 if there is nons
Constraints
・1<=n<=2 * 10^5
• 2 ≤ riceBagsli] = 10^6
