<html>
	<head>
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>sadi.me</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<style>
				body{
					width: 100%;
				}
				table {
				  font-family: arial, sans-serif;
				  border-collapse: collapse;
				  max-width: 100%;
				}
				td, th {
				  border: 1px solid #dddddd;
				  text-align: center;
				  
				}
				
				td {
					border-bottom: 1pt solid rgba(6, 84, 196, 0.5);
					border-top: 1pt solid rgba(6, 84, 196, 0.5);
					border-right: 1pt solid rgba(6, 84, 196, 0.5);
					padding: 0.7em;
				}
				
				th{
					font-weight: bold;
					background-color: #0B62A1;
					color: white;
					text-align: center;
				}
				
				tr.done{
					background-color: #C9FBA1;
				}
				tr.done:hover{
					background-color: #B3D7FC;
				}
				/*
				tr:nth-child(even) {
				  background-color: #F0F2F9;
				  font-size: 0.6em;
				}
				tr:nth-child(odd) {
				  background-color: #EAECF2;
				  font-size: 0.6em;
				}*/
				a:hover{
					color: #FD6403;
				}
				body{
					font-size: 0.8em;
				}
				tr:hover{
					background-color: #D5D0CC;
				}
				
				.heading{
					font-weight: bold;
					font-family: Courier, monospace;
					font-size: 1.3em;
					text-align: left;
					color: #1D1E20;
					background: #F2F5F2;
				}
				.heading:hover{
					text-align: center;
					font-size: 1.3em;
				}
				
	</style>
	</head>
	

	
	<body> 
		
		<a href="mailto:abdotalaatfcih@gmail.com">email: abdotalaatfcih@gmail.com</a>

		<table>
		<div class="heading">Pattern-00: Sliding Window(07)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Maximum Sum Subarray of Size K (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/find-maximum-minimum-sum-subarray-size-k/" target="_blank">geeks <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/MaximumSumSubarrayofSizeK.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>0</td> <!-- Recoded -->
				<td>0</td> <!-- Review1 -->
				<td>simplicity is the main idea to solve the issue </td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Smallest Subarray with a given sum (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.educative.io/collection/5668639101419520/5671464854355968" target="_blank">educative <br> </a>
					<a href="https://leetcode.com/problems/minimum-size-subarray-sum/" target="_blank">leet (medium) <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/SmallestSubArrayWithAGivenSum.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>2</td> <!-- Recoded -->
				<td>2</td> <!-- Review1 -->
				<td>smallest subarray whose sum >= K</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>03</td> <!-- LID -->
				<td>Longest Substring with At Most K Distinct Characters (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.lintcode.com/problem/longest-substring-with-at-most-k-distinct-characters/description" target="_blank">lint <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>
					<a href="https://github.com/SadiHassan/leet/blob/master/Hard/longest-substring-with-at-most-k-distinct-characters.cpp">YES<br>(poor version with map)</a> <br><br>
					<a href="https://github.com/SadiHassan/leet/blob/master/Hard/longest-substring-with-at-most-k-distinct-characters%20_BETTER_V2.cpp">YES<br>(Better version I coded)</a>
				</td>  <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>2</td> <!-- Recoded -->
				<td>2</td> <!-- Review1 -->
				<td>Solved using map. Need to understand/implement an O(n) solution and code. Must review! <br>
				UPDATE -- Solved the O(n) solution. It was nice. Will be good to have another review after some days.
				</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>04</td> <!-- LID -->
				<td>Fruits into baskets (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/fruit-into-baskets/" target="_blank">leet <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/904_Fruit_Into_Baskets.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>1</td> <!-- Recoded -->
				<td>1</td> <!-- Review1 -->
				<td>Solved using map. Need to understand/implement an O(n) solution and code. Must review!</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>05</td> <!-- LID -->
				<td>Longest Substring Without Repeating Characters (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/longest-substring-without-repeating-characters/" target="_blank">leet <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/3_Longest_Substring_Without_Repeating_Characters.cpp">YES</a></td> <!-- Code -->
				<td>YES</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>I solved this problem before, but I am not understanding my code!!! Now, again solved using map. Need to understand/implement an O(n) solution and code. Must review! I took help from the solution, so, it was not a glorified work of solving problem, so, I should check it back later must!!!</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>Ext-01</td> <!-- LID -->
				<td>Max value from Sliding Window</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/sliding-window-maximum/" target="_blank">leet(different problem) <br> </a>
					<a href="https://www.geeksforgeeks.org/sliding-window-maximum-maximum-of-all-subarrays-of-size-k/" target="_blank">geeks(different problem)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Hard/239_Sliding_Window_Maximum.cpp">YES</a></td> <!-- Code -->
				<td>YES</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>Monotonic Dequeue understood. Need to solve similar problems listed in the sheet</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>Ext-02</td> <!-- LID -->
				<td>No of sub-arrays whose sum = K (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/subarray-sum-equals-k/" target="_blank">leet<br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/560_No_of_subarrays_whose_sum_equals_K.cpp">YES<br>[O(n2) solution worked]</a></td> <!-- Code -->
				<td>YES</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>There is a hashmap based solution in leet link, need to understand !!</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>06</td> <!-- LID -->
				<td>Longest Substring with Same Letters after Replacement (hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/longest-repeating-character-replacement/" target="_blank">leet-424</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/424_Longest_Repeating_Character_Replacement.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>I thought a lot and made it complicated. Finally checked solution, I was very close to the solution and the key thoughts were same. Need review.</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>07</td> <!-- LID -->
				<td>Longest Subarray with Ones after Replacement (hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/max-consecutive-ones-iii/" target="_blank">leet-1004</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/1004_Max_Consecutive_Ones_III.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>Solved in one pass. Because of similarity with the previous one (Khikz!)</td> <!-- Notes -->
			</tr>
			
		</table> </br></br>
		
		
		<table>
		<div class="heading">Pattern-01: Two Pointers(08)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr class="done">
				<td>01</td> <!-- LID -->
				<td>Pair with Target Sum (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/count-pairs-with-given-sum/">geeks (count pairs with given sum) <br> </a>
					<a href="https://coderbyte.com/algorithm/two-sum-problem">coderbyte (two sum problem) <br> </a>
					<a href="https://leetcode.com/problems/two-sum/">leet (two sum) <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/abdotalaat/problem-solving/blob/master/src/main/java/com/abdotalaat/problems/TwoSum.java">YES</a></td> <!-- Code -->
				<td>YES</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Use the Map as auxiliary data structure to save the previous value </td> <!-- Notes -->
			</tr>

			<tr >
				<td>02</td> <!-- LID -->
				<td>Remove Duplicates (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/remove-duplicates-from-sorted-list/">83. Remove Duplicates from Sorted List<br> </a>
					<a href="https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/">82. Remove Duplicates from Sorted List II<br> </a>
					<a href="https://leetcode.com/problems/remove-duplicates-from-sorted-array-ii/">80. Remove Duplicates from Sorted Array II<br> </a>
					<a href="https://leetcode.com/problems/find-the-duplicate-number/">287. Find the Duplicate Number<br> </a>
					
					<a href="https://leetcode.com/problems/duplicate-zeros/">1089. Duplicate Zeros<br> </a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>
					<a href="https://github.com/SadiHassan/leet/blob/master/Easy/83_Remove_Duplicates_from_Sorted_List.cpp">YES - 83 - Remove Duplicates from Sorted List</a> <br>
					<a href="https://github.com/SadiHassan/leet/blob/master/Medium/82_Remove_Duplicates_from_Sorted_List_II.cpp">YES - 82 - Remove Duplicates from Sorted List II</a> <br>
					<a href="https://github.com/SadiHassan/leet/blob/master/Medium/80_Remove_Duplicates_from_Sorted_Array_II.cpp">YES - 80 - Remove Duplicates from Sorted Array II</a> <br>
					<a href="https://github.com/SadiHassan/leet/blob/master/Easy/1089_Duplicate_Zeros.cpp">YES - 1089 - Duplicate Zeros</a> <br>
				
				</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>
					There are many versions of this type of problem, not sure which one to include. So, included all. <br>
					Necessary Notes by Problem : <br><br>
					(83) Simple linked list removal. Need to RECODE and Practice, error prone. See Editorial (if any) to find any cool trick related to 'Two Pointers'. <br><br>
					(82) Lil tricky linked list removal. Need to RECODE and Practice, error prone. See Editorial (if any) to find any cool trick related to 'Two Pointers'. <br><br>
					(80) Solved using Ad-hoc. No need to recode or check-back. Still See Editorial (if any) to find any cool trick related to 'Two Pointers'. <br><br>
					(287) NO NEED TO CODE AGAIN Because it's so easy. BUT check the fats-slow pointer (Cycle Detection) solution in the <a href="https://leetcode.com/problems/find-the-duplicate-number/solution/">Editorial</a> !!!!!
				
				</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02 (A)</td> <!-- LID -->
				<td>Contains Duplicate III <br>(very good problem--learning resource)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/contains-duplicate-iii/">220. Contains Duplicate III<br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/220_Contains_Duplicate_III.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Learning resources- <br><a href="https://www.cnblogs.com/grandyang/p/4545261.html">C++ Map Lower Bound usage</a> <br>
										<a href="https://www.geeksforgeeks.org/check-given-array-contains-duplicate-elements-within-k-distance/">C++ Set usage</a> <br>
										<a href="https://massivealgorithms.blogspot.com/2016/03/leetcode-220-contains-duplicate-iii.html">Java Bucket Sort - O(n)</a> <br>
				</td> <!-- Notes -->
			</tr>

			<tr >
				<td>03</td> <!-- LID -->
				<td>Squares of a Sorted Array (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/squares-of-a-sorted-array/">leet-977<br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/977_Squares_of_a_Sorted_Array.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td> *** MUST THINK *** about two pointer solution!!! I solved two ways, 1) using Min Heap 2) using Sort. None of them are not so efficient (10% speed, 10% memory in leet). Need to improve using two pointer. Must be a fun think!!!</td> <!-- Notes -->
			</tr>

			<tr >
				<td>04</td> <!-- LID -->
				<td>Triplet Sum to Zero (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/3sum/">leet-15</a><br>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/15_3Sum.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Solved with many triel and errors. There should be some cool techniques for this common problem which I should learn to enhance idea... MUST REVIEW + REINVESTIGATE!!!!</td> <!-- Notes -->
			</tr>
				
			<tr >
				<td>05</td> <!-- LID -->
				<td>Triplet Sum Close to Target (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/3sum-closest/">leet-16</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/16_3Sum_Closest.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>06</td> <!-- LID -->
				<td>Triplets with Smaller Sum</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/count-triplets-with-sum-smaller-that-a-given-value/">geeks</a><br>
					<a href="https://www.lintcode.com/problem/3sum-smaller/description">lint</a><br>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/918_Lint_3Sum%20Smaller.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>07</td> <!-- LID -->
				<td>Subarrays with Product Less than a Target (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/subarray-product-less-than-k/"> leet-713</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/713_Subarray_Product_Less_Than_K.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>I couldn't solve this problem (though it was not too hard). I just copied the solution from leet editorial and understood most of it. But not getting why "ans = ans + right - left + 1;" works? Need to REVIEW MUST and there is a logN solution which I need to implement later.</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>08</td> <!-- LID -->
				<td>Dutch National Flag Problem (medium)</td> <!-- Title -->
				<td>
					<a href="https://coderbyte.com/algorithm/dutch-national-flag-sorting-problem">CoderByte</a><br>
					<a href="https://www.geeksforgeeks.org/sort-an-array-of-0s-1s-and-2s/">geeks</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
		</table></br></br>
		
		<table>
		<div class="heading">Pattern-02: Fast and Slow pointers(04) <span style="color: red">&#10084;</span>
		</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Linked List cycle detection</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/linked-list-cycle/solution/">leet </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/141_Linked_List_Cycle.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Start of LinkedList Cycle</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/linked-list-cycle-ii/">leet-142</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/142_Linked_List_Cycle_II.cpp">YES</a></td> <!-- Code -->
				<td>YES</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>This type of problem is stupid to ask in a 40 mins interview. If someone know the solution beforehand, only then he/she can answer(this is my belief, some 1% genius can answer without knowing the solution, but that's really not normal!) However, it is an INTERESTING problem....<a href="https://javabypatel.blogspot.com/2017/05/how-floyds-cycle-finding-algorithm-work.html">This link</a> was useful to understand</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>03</td> <!-- LID -->
				<td>Happy Number</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/happy-number/">leet-202</a> <br>
					<a href="https://www.geeksforgeeks.org/happy-number/">geeks</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/202_Happy_Number.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>04</td> <!-- LID -->
				<td>Middle of a Linked List</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/middle-of-the-linked-list/">leet-876</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/876_Middle_of_the_Linked%20List.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Same concept applied</td> <!-- Notes -->
			</tr>
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-03: Pattern: Merge Intervals(04)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Merge Intervals (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/merge-intervals/"> leet </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/56_Merge_Intervals.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>02</td> <!-- LID -->
				<td>Insert Intervals (Hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/insert-interval/">leet-52</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>03</td> <!-- LID -->
				<td>Interval List Intersections (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/interval-list-intersections/">leet-986</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>04</td> <!-- LID -->
				<td>Conflicting Appointments (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/given-n-appointments-find-conflicting-appointments/">geek</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			


			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-04: Cyclic Sort(05)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr>
				<td>01</td> <!-- LID -->
				<td>Cyclic Sort (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/cycle-sort/">geeks example <br> </a>
					<a href="https://leetcode.com/problems/first-missing-positive/discuss/304741/cyclic-sort-on-runtime-and-constant-space-java-with-comments">leet solution of a HARD problem <br> </a>
					<a href="https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/discuss/307741/Cyclic-Sort-in-O(n)">leet solution of an easy problem<br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-05: In-place Reversal of a LinkedList(03)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>In-place reverse of a linked-list</td> <!-- Title -->
				<td>
					<a href="https://www.educative.io/courses/coderust-hacking-the-coding-interview/lq2j"> educative <br> </a>
					<a href="https://leetcode.com/problems/reverse-linked-list/"> leet <br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/206_Reverse_Linked_List.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Review both recursive and iterative way</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Reverse a sub-list</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/reverse-linked-list-ii/">leet-92<br> </a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/92_Reverse_Linked_List_II.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Solved iteratively with "Runtime: 0 ms, faster than 100.00% of C++ online submissions for Reverse Linked List II.
Memory Usage: 8.6 MB, less than 100.00% of C++ online submissions for Reverse Lnked List II."... Yayyy!!! BUT.... it took a day to come up to this solution and there are recursive explanation in leet editorial which I should check, understand and code.
Also, the solution I did should be recoded. It killed me a lot!!!
</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>03</td> <!-- LID -->
				<td>Reverse every K-element Sub-list (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/reverse-nodes-in-k-group/">leet-25</a><br>
					<a href="https://medium.com/@jimdaosui/reverse-nodes-in-k-group-9d232e4a70a7">medium article</a><br>
					<a href="https://www.geeksforgeeks.org/reverse-a-list-in-groups-of-given-size/">geeks</a><br>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Hard/25_Reverse_Nodes_in_k-Group.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Just used previous solution as a function and created a loop to call it as asked in the problem. It was super easy. Previous problem is the key to remember.</td> <!-- Notes -->
			</tr>
				
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-06: Tree Breadth First Search(07)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Binary Tree Level Order Traversal (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/binary-tree-level-order-traversal/">leet (medium)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/102_Binary_Tree_Level_Order_Traversal.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Reverse Level Order Traversal (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/binary-tree-level-order-traversal-ii/">leet-107 (easy)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/107_Binary_Tree_Level_Order_Traversal_II.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			 
			<tr >
				<td>03</td> <!-- LID -->
				<td>Zigzag Traversal (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/">leet-103 (medium)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/103_Binary_Tree_Zigzag_Level_Order_Traversal.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>04</td> <!-- LID -->
				<td>Level Averages in a Binary Tree (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/average-of-levels-in-binary-tree/">leet-637 (easy)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/637_Average_of_Levels_in_Binary_Tree.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>05</td> <!-- LID -->
				<td> Minimum Depth of Binary Tree (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/minimum-depth-of-binary-tree/">leet-111 (easy)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/111_Minimum_Depth_of_Binary_Tree.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>06</td> <!-- LID -->
				<td> Level Order Successor (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/level-order-successor-of-a-node-in-binary-tree/">geeks</a> <br>
					<a href="https://www.lintcode.com/problem/binary-tree-level-order-traversal-ii/description">lint</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/70_LINT_Binary_Tree_Level_Order_Traversal_II.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>07</td> <!-- LID -->
				<td> Connect Level Order Siblings (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/populating-next-right-pointers-in-each-node/">leet-116</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/116_Populating_Next_Right_Pointers_in_Each_Node.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Sweet!</td> <!-- Notes -->
			</tr>	
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-07: Tree Depth First Search(05)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Binary Tree Path Sum(easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/path-sum/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/112_Path_Sum.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Easy problem but took several attempts tp get accepted. need <strong> PRACTICE </strong> to write bug free code at one shot!!!</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>All Paths for a Sum (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/path-sum-ii/">leet-113</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/113_Path_Sum_II.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Easy problem but took several attempts tp get accepted. need <strong> PRACTICE </strong> to write bug free code at one shot!!!</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>03</td> <!-- LID -->
				<td>Sum of Path Numbers (medium)</td> <!-- Title -->
				<td>
					<a href="">PROBLEM NOT FOUND</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td></td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>04</td> <!-- LID -->
				<td>Path With Given Sequence (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/check-root-leaf-path-given-sequence/">geeks</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td></td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>05</td> <!-- LID -->
				<td>Count Paths for a Sum (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/print-k-sum-paths-binary-tree/">geeks</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td></td> <!-- Notes -->
			</tr>
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-08: Two Heaps(03)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Find the Median of a Number Stream (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/find-median-from-data-stream/">leet</a> <br>
					<a href="https://www.geeksforgeeks.org/median-of-stream-of-integers-running-integers/">geeks(without STL)</a> <br>
					<a href="https://www.geeksforgeeks.org/median-of-stream-of-running-integers-using-stl/">geeks(++STL)</a> <br>
					<a href="https://algorithmsandme.com/median-of-integers-stream/">A nice Article</a>
					
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Hard/295_Find_Median_from_Data_Stream.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Interesting insight in the solution. An article can be written with clear explanation</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Sliding Window Median (hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/sliding-window-median/">leet-480</a> <br>
					
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Hard/480_Sliding_Window_Median_ACCEPTED.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Solved the same way as previous problem. Instead of priority_queue, used multiset, because it allows to erase where pq doesn't allow that.<br>
				... ... ..Practice!!!</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>03</td> <!-- LID -->
				<td>Maximize Capital (hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/ipo/">leet-502</a> <br>
					
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-09: Subsets(06)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Subsets (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.educative.io/collection/page/5668639101419520/5671464854355968/5670249378611200">educative (easy)</a> <br>
					<a href="https://leetcode.com/problems/subsets/">leet (medium)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/78_Subsets.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Need to read solution explained in educative. I solved it recursively, but they wrote something with BFS which might be interesting!</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Subsets with duplicates (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.educative.io/collection/page/5668639101419520/5671464854355968/5654100301578240">educative (easy)</a> <br>
					<a href="https://leetcode.com/problems/subsets-ii/">leet (medium)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/90_SubsetsII.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>My solution is not so good(though accepted). Need to understand better solution(using BFS) from educative same as the previous one.</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>03</td> <!-- LID -->
				<td>Permutations (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.educative.io/collection/page/5668639101419520/5671464854355968/5720758194012160">educative (medium)</a>
					<a href="https://leetcode.com/problems/permutations/">leet (medium)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/46_Permutations.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>	
			
			<tr>
				<td>04</td> <!-- LID -->
				<td>String permutations by changing case (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/permute-string-changing-case/">geeks</a> <br>
					<a href="https://leetcode.com/problems/letter-case-permutation/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>05</td> <!-- LID -->
				<td>Balanced Parentheses (hard)</td> <!-- Title -->
				<td>
					<a href="https://medium.com/@gianpaul.r/balanced-parentheses-problem-6306083bc10d">medium</a> <br>
					<a href="https://leetcode.com/problems/generate-parentheses/">leet</a> 
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>06</td> <!-- LID -->
				<td>Unique Generalized Abbreviations (hard)</td> <!-- Title -->
				<td>
					<a href="https://www.lintcode.com/problem/generalized-abbreviation/description">lint</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-10: Modified Binary Search(07)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01 (A)</td> <!-- LID -->
				<td>Basic Binary Search (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/binary-search/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/704_Binary_Search.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>01 (B)</td> <!-- LID -->
				<td>Order Agnostic Binary Search --????(easy)</td> <!-- Title -->
				<td>
					
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Problems not found, maybe it's a new problem listed in educative only</td> <!-- Notes -->
			</tr>

			<tr>
				<td>02</td> <!-- LID -->
				<td>Ceiling of a number(medium)</td> <!-- Title -->
				<td>
					<a href="https://algorithmsandme.com/ceiling-in-sorted-array/">algorithms_and_me</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Is it the correct problem they are asking for?</td> <!-- Notes -->
			</tr>

			<tr>
				<td>03</td> <!-- LID -->
				<td>Next Letter(medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/find-smallest-letter-greater-than-target/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>04</td> <!-- LID -->
				<td>Number Range(medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/34_First_and_last_position_of_element_in_sorted_array.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Is it the correct problem they are asking for?</td> <!-- Notes -->
			</tr>

			<tr>
				<td>05 (A)</td> <!-- LID -->
				<td>Search in a rotated sorted array(medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/search-in-rotated-sorted-array/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>05 (B)</td> <!-- LID -->
				<td>Single element in a rotated sorted array(medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/single-element-in-a-sorted-array/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>05 (C) educative</td> <!-- LID -->
				<td>Single in an INFINITE rotated sorted array(medium)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/find-position-element-sorted-array-infinite-numbers/">geeks</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>06</td> <!-- LID -->
				<td>Minimum Difference Element (medium)</td> <!-- Title -->
				<td>
					<a href="">TBD</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>07</td> <!-- LID -->
				<td>Bitonic Array Maximum (easy)</td> <!-- Title -->
				<td>
					<a href="https://www.includehelp.com/icp/maximum-value-in-a-bitonic-array.aspx">includehelp</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-11: Top 'K' Elements(11)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr class="done">
				<td>01</td> <!-- LID -->
				<td>Top K Numbers(easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/top-k-frequent-elements/">leet  (Top K Frequent Elements)(medium)</a><br>
					<a href="https://leetcode.com/problems/top-k-frequent-words/">leet  (Top K Frequent Words)(medium)</a> 
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/347_Top_K_Frequent_Elements.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td><a href="https://zpjiang.me/2017/11/13/top-k-elementes-system-design/">Nice Reading!</a> Template about pair and priority_queue. Need to practive PQ Min/Max heap with Pair data structure, no need to create a new class as we can use Map.Entry as class and to get the value entry.getValue()/getKey(), we need to read about Comparator interface and compare method</td> <!-- Notes -->
			</tr>
			
			<tr >
				<td>02</td> <!-- LID -->
				<td>Kth Smallest Number (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/kth-largest-element-in-an-array/">leet(medium)</a><br>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/215_Kth_Largest_Element_in_an_Array.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>03</td> <!-- LID -->
				<td>K' Closest Points to the Origin (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/k-closest-points-to-origin/">leet(medium)</a><br>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td> <a href="https://github.com/SadiHassan/leet/blob/master/Medium/973_K_Closest_Points_to_Origin.cpp"> YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Solved with priority_queue. There is a DivNConquer solution in the editorial which might be interesting</td> <!-- Notes -->
			</tr>
			
			<tr class="">
				<td>04</td> <!-- LID -->
				<td>K' Connect Ropes (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/discuss/interview-question/344677/Amazon-or-Online-Assessment-2019-or-Min-Cost-to-Connect-Ropes/">leet(easy)</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">NA</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Solved with priority_queue. There is a DivNConquer solution in the editorial which might be interesting</td> <!-- Notes -->
			</tr>

			<tr >
				<td>05</td> <!-- LID -->
				<td>Top 'K' Frequent Numbers (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/top-k-frequent-elements/">leet(medium)</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/347_Top_K_Frequent_Elements.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>06</td> <!-- LID -->
				<td>Frequency Sort (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/sort-characters-by-frequency/">leet(medium)</a><br>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="">TODO</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>07</td> <!-- LID -->
				<td>Kth Largest Number in a Stream (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/kth-largest-element-in-a-stream/">leet(easy)</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">TODO</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>08</td> <!-- LID -->
				<td>'K' Closest Numbers (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/find-k-closest-elements/">leet(medium)</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">TODO</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>09</td> <!-- LID -->
				<td>Maximum Distinct Elements (medium)</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/maximum-distinct-elements-removing-k-elements/">geeks</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">TODO</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Is it the correct problem?</td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>10</td> <!-- LID -->
				<td>Sum of Elements (medium)</td> <!-- Title -->
				<td>
					<a href="">PROBLEM NOT FOUND</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">TODO</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>11</td> <!-- LID -->
				<td>Rearrange String (hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/reorganize-string/">leet(medium)</a><br>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td><a href="">TODO</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Is it the correct problem?</td> <!-- Notes -->
			</tr>
				
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-12: K-way merge(04)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>Merge K-Sorted List (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/merge-k-sorted-lists/">leet (Hard)</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Hard/23_Merge_k_Sorted_Lists.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr >
				<td>01 (Easier Version)</td> <!-- LID -->
				<td>Merge Two Sorted List (easy)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/merge-two-sorted-lists/">leet (easy)</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/21_Merge_Two_Sorted_Lists.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>02</td> <!-- LID -->
				<td>Kth Smallest Number in M Sorted Lists (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/">leet (medium)</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			
			
		</table><br><br>
		
		
		
		<table>
		<div class="heading">Pattern-13: 0/1 Knapsack (Dynamic Programming)(04)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01(A)</td> <!-- LID -->
				<td>0/1 Knapsack (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/coin-change/">leet - Coin Change (Minimum No of coins required to make a sum)</a> <br>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/322_Coin_Change.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>01(B)</td> <!-- LID -->
				<td>0/1 Knapsack (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/coin-change-2/">leet - Coin Change 2 (No of ways to make a sum using some coins)</a>
					<a href="https://leetcode.com/problems/coin-change-2/discuss/222400/clear-explanation-like-01-knapsack-problem">(Explanation)</a> <br>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>02</td> <!-- LID -->
				<td>Equal Subset Sum Partition (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/partition-equal-subset-sum/">leet - Partition Equal Subset Sum </a> 
					<a href="https://leetcode.com/problems/partition-equal-subset-sum/discuss/90592/01-knapsack-detailed-explanation">(Explanation)</a> <br>
					<a href="https://www.educative.io/collection/page/5668639101419520/5633779737559040/5752754626625536">educative</a> <br>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>03</td> <!-- LID -->
				<td>Subset Sum</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/subset-sum-problem-dp-25/">geeks</a> <br>
					<a href="https://www.educative.io/collection/page/5668639101419520/5633779737559040/5646239437684736">educative</a> <br>	
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>04</td> <!-- LID -->
				<td>Minimum Subset Sum Difference</td> <!-- Title -->
				<td>
					<a href="https://www.geeksforgeeks.org/partition-a-set-into-two-subsets-such-that-the-difference-of-subset-sums-is-minimum/">geeks</a> 
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-14: Topological Sort(06)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			Topological Sort (medium)
			Tasks Scheduling (medium)
			Tasks Scheduling Order (medium)
			All Tasks Scheduling Orders (hard)
			Alien Dictionary (hard)
			<tr class = "done">
				<td>01</td> <!-- LID -->
				<td>Course Schedule (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/course-schedule/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/207_Course_Schedule.cpp">YES</a></td> <!-- Code -->
				<td>1</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Coded BFS based approach. Need to code DFS one later \n connected grraph or not  \n  has cycle (isvisted,isexplered)</td> </td> <!-- Notes -->
			</tr>

			<tr class = "done">
				<td>02</td> <!-- LID -->
				<td>Course Schedule II (medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/course-schedule-ii/">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/207_Course_ScheduleII.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Coded BFS based approach. Need to code DFS one later<!-- Notes -->
			</tr>

			<tr>
				<td>02</td> <!-- LID -->
				<td>Course Schedule III (Hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/course-schedule-iii/">leet</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>03</td> <!-- LID -->
				<td>Alien Dictionary (Hard)</td> <!-- Title -->
				<td>
					<a href="https://www.lintcode.com/problem/alien-dictionary/description">lint</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			<tr>
				<td>04</td> <!-- LID -->
				<td>Longest Increasing Path in a Matrix (Hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/longest-increasing-path-in-a-matrix/">leet</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>05</td> <!-- LID -->
				<td>Sequence Reconstruction (Medium)</td> <!-- Title -->
				<td>
					<a href="https://www.lintcode.com/problem/sequence-reconstruction/description">lint</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>

			<tr>
				<td>06</td> <!-- LID -->
				<td>Sort Items by Groups Respecting Dependencies (Hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/sort-items-by-groups-respecting-dependencies/">lint</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
		</table><br><br>
		
		<table>
		<div class="heading">Pattern-15: Miscellaneous (n)</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr >
				<td>01</td> <!-- LID -->
				<td>K-th Smallest Number (Hard)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/kth-largest-element-in-an-array/">leet</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/215_Kth_Largest_Element_in_an_Array.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Used priority_queue and it was trivial. There is a <a href="https://leetcode.com/problems/kth-largest-element-in-an-array/discuss/361946/The-quick-selection-algorithm-implemented-by-Cpp-beating-97.41-submissions.">better solution</a> that uses Quick selection technique as used in Quick Sort (refer to the Algorithm course of Stanford which I </td> <!-- Notes -->
			</tr>
				
			<tr >
				<td>02</td> <!-- LID -->
				<td>Remove Nth Node From End of List (Medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/remove-nth-node-from-end-of-list/">leet</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/19_Remove_Nth_Node_From_End_of_List.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>There is a One pass solution in leet editorial. *****Need***** to understand that. </td> <!-- Notes -->
			</tr>

			<tr >
				<td>03</td> <!-- LID -->
				<td>K Closest Points to Origin (Medium)</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/k-closest-points-to-origin/">leet</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/973_K_Closest_Points_to_Origin.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Template for Min Heap with pair data type !!!!! TEMPLATE MUST!!!</td> <!-- Notes -->
			</tr>
			<tr >
				<td>04</td> <!-- LID -->
				<td>Nex greater element-1</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/next-greater-element-i/">leet</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Easy/496_Next_Greater_Element_I.cpp">YES</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Stack based implementation</td> <!-- Notes -->
			</tr>

			<tr>
				<td>04</td> <!-- LID -->
				<td>Nex greater element-1</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/problems/next-greater-element-ii/">leet</a>
				</td> <!-- Links -->
				<td>DONE</td> <!-- Read -->
				<td><a href="https://github.com/SadiHassan/leet/blob/master/Medium/503_Next_Greater_Element_II.cpp">Work In Progress</a></td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>Stack based implementation</td> <!-- Notes -->
			</tr>
			
		</table><br><br>
		
		<table>
		<div class="heading">Contest Upsolve</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr>
				<td>01</td> <!-- LID -->
				<td>BWC-07: 1168-Optimize Water Distribution in a Village</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/contest/biweekly-contest-7/problems/optimize-water-distribution-in-a-village">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			<tr>
				<td>02</td> <!-- LID -->
				<td>WC-151: 1169-Invalid Transactions</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/contest/weekly-contest-151/problems/invalid-transactions">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			<tr>
				<td>03</td> <!-- LID -->
				<td>WC-151: 1171-Remove Zero Sum Consecutive Nodes from Linked List</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/contest/weekly-contest-151/problems/remove-zero-sum-consecutive-nodes-from-linked-list">leet</a>
				</td> <!-- Links -->
				<td>YES</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>DO IT MUST</td> <!-- Notes -->
			</tr>
			<tr>
				<td>04</td> <!-- LID -->
				<td>WC-151: 1172-Dinner Plate Stacks</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/contest/weekly-contest-151/problems/dinner-plate-stacks">leet</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
				
			
			
		</table><br><br>
		
		<table>
		<div class="heading">Tutorials and/or Useful Links</div>
			<tr>
				<th>SL</th>
				<th>Title</th>
				<th>Links</th>
				<th>Read</th>
				<th>Code</th>
				<th>SolUnd</th>
				<th>ReCoded</th>
				<th>Review1</th>
				<th>Review2</th>
				<th>Notes</th>
			</tr>
			
			<tr>
				<td>01</td> <!-- LID -->
				<td>C++ Pointer Tutorial</td> <!-- Title -->
				<td>
					<a href="https://gist.github.com/ericandrewlewis/720c374c29bbafadedc9">Eric Lewis' gist</a>
					<a href="https://www.ntu.edu.sg/home/ehchua/programming/cpp/cp4_PointerReference.html">Very good in detail C++ pointer* and Reference& </a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			
			<tr>
				<td>02</td> <!-- LID -->
				<td>Leetcode Patterns (VERY GOOD)</td> <!-- Title -->
				<td>
					<a href="https://medium.com/leetcode-patterns">csgator medium series</a>
				</td> <!-- Links -->
				<td>NA</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				<td>NA</td> <!-- Notes -->
			</tr>
			<tr>
				<td>03</td> <!-- LID -->
				<td>System Design</td> <!-- Title -->
				<td>
					<a href="https://leetcode.com/discuss/career/216554/From-0-to-clearing-UberAppleAmazonLinkedIn">leetcode good discussion</a> <br>
					<a href="https://leetcode.com/discuss/career/229177/My-System-Design-Template">System Design Template</a> <br>
					<a href="https://github.com/donnemartin/system-design-primer">System Design Premier</a> <br>
				</td> <!-- Links -->
				<td>1</td> <!-- Read -->
				<td>NA</td> <!-- Code -->
				<td>NA</td> <!-- SolUnd -->
				<td>NA</td> <!-- Recoded -->
				<td>NA</td> <!-- Review1 -->
				<td>NA</td> <!-- Review2 -->
				 <td><ul>
				 	 <li>Start and be consistent</li>
					 <li>Don't be in a hurry. Enjoy the ride :)</li>
					 <li> Software design template
					 	<ul>
						 <li>What's Expected</li>
						 <li>assumtion phase</li>
						 <li>design target</li>
						 <li>high level design </li>
						 <li>in details design</li>
						 <li> justification</li>
					 	</ul>
						</li>
					 <li></li>
				</ul></td> <!-- Notes -->
			</tr>
			
				
			
			
		</table><br><br>
	</body>
</html>