# Create-an-Object
class MyClass {       // The class   public:             // Access specifier     int myNum;        // Attribute (int variable)     string myString;  // Attribute (string variable) };  int main() {   MyClass myObj;  // Create an object of MyClass    // Access attributes and set values   myObj.myNum = 15;    myObj.myString = "Some text";    // Print attribute values   cout &lt;&lt; myObj.myNum &lt;&lt; "\n";   cout &lt;&lt; myObj.myString;   return 0; }
