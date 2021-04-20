using System;
using System.Collections.Generic;
using System.Text;

namespace LambdaUnitTestExample
{
    public enum Condition {EXCELLENT, GOOD, FAIR, BAD };

    public class Car
    {
        //create class attributes
        public string Make;
        public Condition Condition;
        public int Speed = 0;

        //constructors
        public Car(string carMake, Condition carCondition)
        {
            this.Make = carMake;
            this.Condition = carCondition;
        }

        public Car(int Speed)
        {
            this.Speed = Speed;
        }

    }
}
