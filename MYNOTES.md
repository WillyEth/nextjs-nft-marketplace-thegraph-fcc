



## TAILWIND
 yarn add --dev tailwindcss postcss autoprefixer
 yarn tailwindcss init -p

 

## FRPC Moralis Server
Step 1: Download the windows frp version titled "[frp_0.44.0_windows_amd64.zip]"
Step 2: Replace the frpc.ini contents with the ones provided by your moralis server
Step 3: Now, cd into the frp directory
cd frp
before executing the actual file we have to provide it permissions to since you might be seeing
frpc permission denied
so to do that, we can write
chmod +x frpc.exe
./frpc.exe -c frpc.ini
 
 "moralis:sync": "moralis-admin-cli connect-local-devchain --chain hardhat --moralisSubdomain ppd7cnytowx6.usemoralis.com --frpcPath ./frp/frpc.exe"
  <MoralisProvider initializeOnMount={false}>
yarn global add moralis-admin-cli 

      <MoralisProvider initializeOnMount={false}>
 "moralis": "^2.0.1",
NEXT_PUBLIC_SERVER_URL=https://ppd7cnytowx6.usemoralis.com:2053/server
NEXT_PUBLIC_APP_ID=EmERWDIOwWVmZilh7r35rbHMy9gbzuP0eKbi2pgc

     <MoralisProvider appId={APP_ID} serverUrl={SERVER_URL}>
 <MoralisProvider appId="EmERWDIOwWVmZilh7r35rbHMy9gbzuP0eKbi2pgc" serverUrl="https://ppd7cnytowx6.usemoralis.com:2053/server">

          <MoralisProvider appId={APP_ID} serverUrl={SERVER_URL}>

    "moralis:sync": "moralis-admin-cli connect-local-devchain --chain hardhat --moralisSubdomain ppd7cnytowx6.usemoralis.com --frpcPath ./frp/frpc.exe"




import { ConnectButton } from "@web3uikit/web3"


  "dependencies": {
    "magic-sdk": "^9.0.0",
    "moralis": "1.11.0",
    "next": "12.1.5",
    "react": "18.1.0",
    "react-dom": "18.1.0",
    "react-moralis": "^1.3.5",
    "web3uikit": "^0.0.133"
  },