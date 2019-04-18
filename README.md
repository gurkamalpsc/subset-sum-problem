# subset-sum-problem
The subset sum problem is an important decision problem in Computer Science that inherently has an exponential complexity. Given a data set of positive integers, the problem seeks to find a subset of those values whose sum meets a given target exactly, or as close as possible.
## Real World Applications
### Loading a Truck, Ship, or Plane
Shipping companies are always tyring to achieve efficiency by strategically loading packages into their vehicles. Of course the best scenario is to meet the vehicle's payload limit exactly. Since any finite weight can be expressed as an integer by converting to smaller units, the problem can be expressed as a subset sum problem with the target being the exact weight limit.
### Computer Authentication
Let's say a computer generates a large set of positive integers that get stored instead of a password. A password can then be stored as a subset of those integers by converting symbols to associated integers. When the user types in a password the computer can test whether its associated subset is a solution to the subset sum problem.
## This Repository
### ```integer-algorithm```
The classical version of this problem, where a set of integers is represented as a ```java.util.ArrayList<Integer>```.
### ```itunes_algorithm```
Imagine an iTunes playlist with many songs and a radio station seeking to efficiently broadcast music. The algorithm figures out how to fill up the station's broadcast with a set of songs that match an exact time target down to the second.
## Running the Code
### Prerequesites
* [Java 8](https://www.oracle.com/technetwork/java/javaee/downloads/jdk8-downloads-2133151.html) - Gradle 5.4 requires Java 8 or later to run.
### Command Line
```
git clone https://github.com/gurkamalpsc/subset-sum-problem.git
cd subset-sum-problem
./gradlew run
```
### ```itunes_algorithm```
Imagine an iTunes playlist with many songs and a radio station seeking to efficiently broadcast music. The algorithm figures out how to fill up the station's broadcast with a set of songs that match an exact time target down to the second.
## Built With
* [IntelliJ Idea CE](https://www.jetbrains.com/idea/) - Java & Kotlin IDE
* [Gradle](https://gradle.org/) - Build Tool & Monorepo Management
## License
This project is licensed under the MIT License - see the LICENSE file for details
