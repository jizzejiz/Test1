# Test1

 [Test]
        public void GetMultiplication_Input6point0and7point0_Returns42point0()
        {
            //Arrange
            double number43 = 6.0;
            double number44 = 7.0;

            double expectedResult = number43 * number44;
            Calc testCalc = new Calc(number43, number44);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetMultiplication_Input4point5and12point0_Returns54point0()
        {
            //Arrange
            double number53 = 4.5;
            double number54 = 12.0;

            double expectedResult = number53 * number54;
            Calc testCalc = new Calc(number53, number54);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetMultiplication_Input12point0and14point0_Returns168point0()
        {
            //Arrange
            double number63 = 12.0;
            double number64 = 14.0;

            double expectedResult = number63 * number64;
            Calc testCalc = new Calc(number63, number64);

            //Act
            double actualResult = testCalc.GetMultiplication();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
