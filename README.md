import { createThirdwebClient, getContract } from "thirdweb";
import { defineChain } from "thirdweb/chains";

//ea64296345e2b805df83bcce7b4fd3b6
const client = createThirdwebClient({
  clientId: "YOUR_CLIENT_ID",
});

// 0xB8fe3e0328D5a4F0c6BDdC6ad52481268bD27F9a
const contract = getContract({
  client,
  chain: defineChain(1),
  address: "0xB8fe3e0328D5a4F0c6BDdC6ad52481268bD27F9a",
});
