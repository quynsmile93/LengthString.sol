# LengthString.sol
LengthString.sol
pragma solidity ^0.8.20;
contract ConcatString {
    function concat(string memory a,string memory b) public pure returns(string memory){
        return string(abi.encodePacked(a,b));
    }
}
