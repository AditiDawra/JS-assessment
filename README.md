# JS-assessment
// create a variable to hold your NFT's
let nftCollection = [];


function mintNFT (name, description) {
  let nft = {
    name: name,
    description: description,
   
    
  };
  nftCollection.push(nft);
}


function listNFTs () {
  for (let i = 0; i < nftCollection.length; i++) {
    console.log("Name: " + nftCollection[i].name);
    
    console.log("Description: " + nftCollection[i].description);
    
    
    
  }
}


function getTotalSupply() {
  console.log("Total NFTs: " + nftCollection.length);
}


mintNFT("NEHA", "This is NFT 1");
mintNFT("AMAN", "This is NFT 2");
mintNFT("ANSH", "This is NFT 3");

listNFTs();

 getTotalSupply();
