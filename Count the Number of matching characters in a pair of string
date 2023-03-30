// C++ code to count number of matching
// characters in a pair of strings

# include <bits/stdc++.h>
using namespace std

// Function to count the matching characters
void count(string str1, string str2)
{
	int c = 0, j = 0

	// Traverse the string 1 char by char
	for (int i=0
		i < str1.length()
		i++) {

		// This will check if str1[i]
		// is present in str2 or not
		// str2.find(str1[i]) returns - 1 if not found
		// otherwise it returns the starting occurrence
		// index of that character in str2
		if (str2.find(str1[i]) >= 0
			and j == str1.find(str1[i]))
		c += 1
		j += 1
	}
	cout << "No. of matching characters are: "
	<< c / 2
}

// Driver code
int main()
{
	string str1 = "aabcddekll12@"
	string str2 = "bb2211@55k"

	count(str1, str2)
}
