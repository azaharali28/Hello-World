# Hello-World
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using HelloWorld.Service;
namespace HelloWorld.ConsoleApp
{
    class Program
    {
        static void Main(string[] args)
        {
            var serviceCall = new ServiceCall();
            var msg=serviceCall.GetResponse(null);

           // Console.WriteLine("Hello World");

            Console.WriteLine(msg.Result);
            Console.ReadKey();
