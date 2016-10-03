# Cube Scrambler PHP Class

Tiny PHP class for generating a random Rubik's cube scramble.

## Example Usage

```php
include 'Scrambler.php';

$scrambler = new Scrambler();
echo $scrambler->generate();

// Set length
$scrambler = new Scrambler();
$scrambler->setLength(50);
echo $scrambler->generate();

// Set chance of double and prime moves
$scrambler = new Scrambler();
$scrambler->setChancePrime(10);
$scrambler->setChanceDouble(75);
echo $scrambler->generate();
```

## Example Output

    F' D L2 D F' B L2 U2 D' L' F B D U B2 F2 U2 R F D' L2 B2 R' F R

##License

Cube Scrambler PHP Class is licensed under the [MIT license](http://opensource.org/licenses/MIT), see [LICENSE.md](https://github.com/jamiebicknell/Cube-Scrambler/blob/master/LICENSE.md) for details.