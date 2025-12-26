# experiment2 
##title:2a.implement class mechanism
##source code:
class Square {
  int side;
  int area_of_Square() {
  return  side*side;
  }
  int perimeter_of_Square() {
  return 4*side;
  }
}
class Mechanism {
   public static void main(String[] args) {
     Square sq=new Square();
     sq.side=5;
     int area=sq.area_of_Square();
     int perimeter=sq.perimeter_of_Square();
     System.out.println("Area of square is:"+area);
     System.out.println("Perimeter of square is:"+perimeter);
   }
}
