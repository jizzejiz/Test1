# Test1
 
  [Test]
        public void GetSubtraction_Input3point0and2point0_Returns1point0()
        {
            //Arrange
            double number22 = 3.0;
            double number23 = 3.0;

            double expectedResult = number22 - number23;
            Calc testCalc = new Calc(number22, number23);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }

        [Test]
        public void GetSubtraction_Input12point0and2point0_Returns9point0()
        {
            //Arrange
            double number22 = 12.0;
            double number23 = 9.0;

            double expectedResult = number22 - number23;
            Calc testCalc = new Calc(number22, number23);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
        [Test]
        public void GetSubtraction_Input16point0and12point0_Returns4point0()
        {
            //Arrange
            double number33 = 16.0;
            double number34 = 12.0;

            double expectedResult = number33 - number34;
            Calc testCalc = new Calc(number33, number34);

            //Act
            double actualResult = testCalc.GetSubtraction();

            //Assert
            Assert.AreEqual(expectedResult, actualResult);
        }
