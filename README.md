# Method-chaining-1

#methodchaining 

class car:
    def drive(self):
        print ("the car is driving ")
        return self 
    def stop(self):
        print("the car is stopped")
        return self  
    def repair (self):
        print("the car is repair")
        return self 
        
Car = car()   
Car.drive().stop()


