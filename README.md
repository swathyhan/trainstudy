# trainstudy
this is program is about the trichy train schedule between trichy and chennai.

package trainstudy;
import java.util.*;



public class Trainstudy {

    
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String[] deptimes=new String[15];
        int i,ch,mpop,lpop;
        double total;
        for(i=0;i<15;i++)
        {
            
        
            System.out.println("Enter the Departuretimes["+i+"]");
            deptimes[i]=sc.nextLine();
            
        }
        int[] Passengers={22,119,64,177,21,22,111,87,193,22,11,107,93,162,42};
        System.out.println("Day\tTime\tPassengers");
        String day="";
        for(i=0;i<15;i++)
        {
            if(i>=0 && i<5)
                day="Monday";
            if(i>=0 && i<10)
                day="Tuesday";
            if(i>=11 && i<15)
                day="Wednesday";
            
        }
        System.out.println("1.The most popular train\n2.The least popular train\n3.Average number of passenger travelled on 12.04 train\n4.Whether 6.04 on monday is popular or 6.04 on tuesday\n5.The train has below the 50 passengers\n6.Whether 6.04 train is more popular than 9.04 train\n7.Average number of Passengers on the specified time by the user\n8.exit");
        
                System.out.println("Enter the choice: ");
                ch=sc.nextInt();
                for(i=0;i<2;i++)
                {
                    switch(ch)
                    {
             case 1:
                 System.out.println("1.The most popular train");
                 for(i=0;i<15;i++)
                 {
                    
                    mpop=Passengers[i];
                    if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }else if(mpop<Passengers[i])
                    {
                        Passengers[i]=mpop;
                    }
                    System.out.println("Day:"+day+"\nDeparturetime:"+deptimes[i]+"\nPassengers: "+mpop);
                    break;
                }
                    case 2:
                     System.out.println("The most popular train");
                     for(i=0;i<15;i++)
                     {
                     lpop=Passengers[i];
                     if(lpop>Passengers[i])
                     {
                     Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       
                        }  
                        else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       
                        }
                       else if(lpop>Passengers[i])
                       { 
                       Passengers[i]=lpop;
                       
                          }
                          System.out.println("Day "+day+"\nDeparturetime: "+deptimes[i]+"\nPassenger:" +lpop);
                     }
    
                          break;
                          
                          case 3:
                          total=(Passengers[2]+Passengers[7]+Passengers[12]/3);
                          System.out.println("The average Passengers on 12.04 train is: "+total);
                          break;
                          case 4:
                          System.out.println("Whether 6.04 on monday is popular or 6.04 on tuesday");
                          if(Passengers[0]>Passengers[5])
                          System.out.println("6.04 on monday is popular ");
                          else
                          {
                          System.out.println("6.04 on tuesday is more popular");
                          }
                          case 5:
                         System.out.println("The train has below the 50 passengers");
                         for(i=0;i<15;i++)
                         {
                             if(Passengers[i]<50)
                             {
                                 System.out.println("Day "+day+"\nTime "+deptimes[i]+"\nPassengers: "+Passengers[i]);
                                 
                             }
                         }break;
                          case 6:
                              System.out.println("Whether 6.04 train is more popular on 9.04 train");
                              if(Passengers[0]+Passengers[5]+Passengers[10]>Passengers[1]+Passengers[6]+Passengers[11]);
                              System.out.println("6.04 train is more popular than 9.04");
                             
                              {
                                  System.out.println("9.04 train is more popular than 6.04");
                                      
                              }
                              break;
                          case 7:
                              System.out.println("Average number of Passengers on the specified time by user");
                              System.out.println("Enter the train: ");
                              deptimes[i]=sc.nextLine();
                              System.out.println("Day"+day+"\nTimes: "+deptimes[i]+"\nPassengers"+Passengers[i]);
                              break;
                          case 8:
                              System.exit(0);
                          default:
                              System.out.println("Invalid choice");
                         }
                }}}
