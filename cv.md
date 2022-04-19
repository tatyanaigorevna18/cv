**Kolbasnikova Tatyana**

*Student*

![my photo](https://github.com/tatyanaigorevna18/cv1/blob/markdown-cv/uufQhn3A17zPPwN7OBBVtwBSRqsu2uPu6UTWlQpTgE2W_UtC2a2ga7-IMKSmy3OhyJ7JLEBMCJeP6H2G2vx5qLHi.jpg)

**Contact information:**

*Phone:+37533627638*

*E-mail: tk.taniy@gmail.com*

*Telegram: @tatyana_igorevna18*


**Briefly About Myself**

My name is Tatiana Kolbasnikova. I am a student The University named after Peter Mironovich Masherov. At the moment I am studying in the 1st year of the Faculty of Mathematics and Information Technology in the specialty information resource management. 
These six months I studied work in Excel, Microsoft Access, Visual Studio, learned how to work in the Windows and Linux command line.
I consider myself a hardworking person, I learn quickly,very communication person.

**Skills:**

* C++

* HTML

* Adobe Photoshop

* Excel,Microsoft Access

* GitHub

**Code example:**
```bsl
class triangle {
protected:
  double a,b,h;
public:
  triangle(double a, double h,double b) {
    this->a = a;
    this->h = h;
    this->b = b;
  }
  double s() {
    return (a*a*sqrt(3))/4;
  }
};

class trapeze :public triangle {
public:
  trapeze(double a,double b, double h) :triangle(a,b, h) {
  }
  double s() {
    return (h*((a+b)/2));
  }
};
int main() {
  SetConsoleOutputCP(1251);
  double a,b,h;
  cout << "Введите сторону треугольника:\n";
  cin >> a;
  cout << "Введите 2 сторону трапеции:\n";
  cin >> h;
  cout << "Введитe высоту:\n";
  cin >> b;
  triangle OSN(a,b, h);
  trapeze VTOR(a,b, h);
  cout << "Площадь треугольника равен: " << OSN.s() << "\n";
  cout << "Площадь трапеции равен:" << VTOR.s() << "\n";
  system("pause");
  return 0;
}
```

**Languages:**

- Belarusian

- Russian

- English

*Follow my work on GitHub* *https://github.com/tatyanaigorevna18 🥰 🤫 😏*





