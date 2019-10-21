```java
package Queue;
/*
 * 队列的数组实现
 */

public class QueueArray {
	
	//创建数组
	private int a[];
	//队头指针front 队尾指针rear 数组实际容量size
	private int front,rear,size;
	//动态创建数组容量	
	private int capacity;
	
	
	//初始化变量 构造方法
	public QueueArray(int capacity) {
		
		//先把参数传到当前对象的变量
		this.capacity = capacity;
		//动态创建数组
		a = new int[capacity];
		//数组为空size=0
		front = rear = 0;
		
			
	}
	
	//入队
	void Enqueue(int data) {
		
		a[rear] = data;
		rear++;
		
	}
	
	

}

```

