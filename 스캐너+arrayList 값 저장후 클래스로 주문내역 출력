package sec03.exam01;
import java.util.Scanner;
import java.util.ArrayList;

 class Order { 
String name;	
String item;
int count;
	 public Order( String name , String item , int count) { 
	this.name = name; 
	this.item = item;
	this.count = count;
	} 
 
 public static void printMenu (ArrayList <Order> orders ) {  
	 
	 
		System.out.println("\n=====주문 내역=====");
		for( Order o : orders ) {
			System.out.println(o.name + "-" + o.item + " (" + o.count + ")");
 
		}
        }
	public static void main(String[] args) {
    ArrayList <Order> orders = new ArrayList <>(); 
    Scanner sc = new Scanner(System.in);
    
    System.out.println("주문 개수를 입력하세요:");
     int ordercount = sc.nextInt();
    sc.nextLine();

	for(int i = 0 ; i < ordercount; i++ ) {
		System.out.println((i+1)+"번째 주문 정보를 입력하세요");
		System.out.println("고객이름:");
		String name = sc.nextLine();
		System.out.println("상품이름:");
		String item = sc.nextLine();
		System.out.println("개수:");
		int count = sc.nextInt();
	    sc.nextLine();
	orders.add(new Order(name , item , count ));
	}
	
	printMenu(orders);
	}
	}
