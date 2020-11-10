class Square():
    
    def perimeter(self, side = 1.0):
        self.side = side
    
    #setter method
    def setSide(self, side):
        if (side <= 0):
            print ("The perimeter of square is 0 because the invalid value")
        else:
            print ("The perimeter of square is ",(side*4))
            
            
squareSide = Square()
print(squareSide.setSide(-1))
print(squareSide.setSide(1))
