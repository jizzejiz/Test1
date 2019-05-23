# Test1
 {
     
     [Test]
        public void GetAddition_Input2point4and8point6_Returns11point0()
        {
            //Arrange
            double number1 = 2.4;
            double number2 = 8.6;

            double expectedResult = number1 + number2;
            Calc testCalc = new Calc(number1, number2);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }
        [Test]
        public void GetAddition_Input5point5and9point6_Returns15point1()
        {
            //Arrange
            double number3 = 5.5;
            double number4 = 9.6;

            double expectedResult = number3 + number4;
            Calc testCalc = new Calc(number3, number4);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);

        }


        [Test]
        public void GetAddition_Input3point3and7point3_Returns10point6()
        {
            //Arrange
            double number5 = 3.3;
            double number6 = 7.3;

            double expectedResult = number5 + number6;
            Calc testCalc = new Calc(number5, number6);

            //Act
            double actualResult = testCalc.GetAddition();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
