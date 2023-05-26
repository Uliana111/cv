# Uliana ALekseeva
### Student
##
### Contact information:
**Phone:** +375 29 2624689

**E-mail:** articl1940@gmail.com
##
 > About Myself:
 
I am a first year university student. Before entering, I was not interested in programming, but when I started studying, I decided to develop in this field of activity. Because of the desire to start understanding this, I decided to take individual courses in programming and coding. From the very beginning of the training, I began to have difficulties with understanding the educational material, but this topic was already of interest to me. Then I started to understand the basics. In the first half of the year we worked on editors Inkscape, Adobe Photoshop and Download Blender.

Since I had to learn French at school, I learned English on my own in my spare time. Now I attend foreign language courses, I study English in a group. At the university, we are taught professional vocabulary of the English language. Now I understand that I want to develop in the field of programming and work in my specialty. This is my first cv and my first project. However, I am going to develop my level of English and programming further.
##
**Applications and programs with which I had a chance to work:**
+ Adobe Photoshop, Inkscape
+ Blender
+ C++
+ Git, GiitHub
##
**Languages:**
+ Russian, Belarusian
+ French (in the learning process)
+ Italian
+ English (level A2, not documented, in the learning process)
##
**Code example:**
> Input-output of a vector of fractional numbers using iterators.

int main(int argc, char* argv[]) {
	
	vector<double> v;

	istream_iterator<double> cin_iter(cin);
	
	istream_iterator<double> cin_end;
	while (cin_iter != cin_end) { 
		double x = *cin_iter; 
		v.push_back(x); 
		cin_iter++;
	}
	
	vector<double>::iterator iter;
	iter = v.begin(); 
	while (iter < v.end()) { 
		cout << *iter << endl;
		iter++; 
	}
	system("pause");
	return 0;}
