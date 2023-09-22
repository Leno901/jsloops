// Create a variable to hold your NFTs
const NFTs = [];

// Define a function to mint an NFT and add it to the collection
function mintNFT(name, description) {
  const nft = {
    name: name,
    description: description,
  };
  NFTs.push(nft);
}

// Define a function to list all NFTs in the collection
function listNFTs() {
    NFTs.forEach((nft, index) => {
    console.log(`NFT #${index + 1}:`);
    console.log(`Name: ${nft.name}`);
    console.log(`Description: ${nft.description}`);
    console.log("--------------------------");
  });
}

// Define a function to get the total number of minted NFTs
function getTotalSupply() {
  return NFTs.length;
}

// Call the functions to mint NFTs
mintNFT("NFT 1", "This is the first NFT", "image1.jpg");
mintNFT("NFT 2", "This is the second NFT", "image2.jpg");

// Call the function to list NFTs
console.log("List of NFTs:");
listNFTs();

// Call the function to get the total supply
console.log(`Total NFTs minted: ${getTotalSupply()}`);


