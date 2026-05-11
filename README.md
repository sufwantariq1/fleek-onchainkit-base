## Fleek + OnchainKit with Base & Jstack

## Overview

This project integrates **OnchainKit** and the **Base Pixel** font on Fleek, leveraging the **Base Pixel** typeface for an expressive and digital-native experience. Additionally, the project is deployed using Fleek’s Next.js adapter, ensuring edge-optimized performance and decentralized hosting.

## Technologies Used

- **OnchainKit**: A toolkit for onchain interactions
- **Base**: Layer 2 scaling solution for Ethereum
- **Base Pixel Typeface**: A custom font created by Base’s Creative Office and Clément Cases
- **Fleek Next.js Adapter**: Deployment solution for Next.js applications

## Base Pixel Typeface

**Base Pixel** is a unique typeface designed by **Clément Cases** in collaboration with **Base's Creative Office**. It plays with the contrast between traditional typography and the digital world, with each weight representing a 'degradation' of resolution. Minting the Base Pixel NFT provides access to the font and a full commercial license. All proceeds go to the designer.

## Running the Template Locally

To run this template locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone <repo-url>
   ```
2. Navigate into the project directory:
   ```sh
   cd base-fleek
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Create a `.env.local` file in the project root and add the following environment variables:

   ```
   NEXT_PUBLIC_ONCHAINKIT_API_KEY=
   ```

   You can obtain the `ONCHAINKIT_API_KEY` from your [CDP dashboard](https://portal.cdp.coinbase.com/projects/api-keys/client-key).

5. Start the development server:
   ```sh
   npm run dev
   ```

## Deployment with Fleek

This project uses **Fleek’s Next.js adapter** for seamless deployment to the Fleek Network.

### Prerequisites

Ensure you have the following installed:

- **Node.js** (Version 18+)
- **Fleek CLI** (Version 3+)
- **Next.js Application**

### Installation

To install the Fleek Next.js adapter, run:

```sh
# Using npm
npm install @fleek-platform/next

# Global installation
npm install @fleek-platform/next -g
```

### Configuring Edge Runtime

For server-side routes, configure the runtime:

```js
export const runtime = "edge";
```

### Building the Application

Use the Fleek Next.js adapter to build your project:

```sh
npx fleek-next build

# Or if installed globally
fleek-next build
```

If running the command outside the project root, specify the path:

```sh
fleek-next build -p path/to/my/repo
```

### Deploying the Application

1. **Create a Fleek Function**:

   ```sh
   fleek functions create
   ```

   Note the function name for the next step.

2. **Deploy the Application**:
   ```sh
   fleek functions deploy --bundle=false --path .fleek/dist/index.js --assets .fleek/static
   ```
   If not logged in, you will be prompted to log in and select your project.

### Deployment Output

Upon successful deployment, you will receive a Fleek Function URL:

```sh
✅ Success! Deployment completed.
🔗 https://your-deployment.functions.on-fleek.app
🔗 https://fleek.network/services/your-ipfs-hash
```

## Notes
- For more information on Next.js support in Fleek, refer to the [official documentation](https://fleek.xyz/docs).
- commit 2
- commit 3
commit 4
commit 5
commit 6
commit 7
commit 8
commit 9
commit 10
commit 11
commit 12
commit 13
commit 14
commit 15
commit 16
commit 17
commit 18
commit 19
commit 20
commit 21
commit 22
commit 23
commit 24
commit 25
commit 26
commit 27
commit 28
commit 29
commit 30
commit 31
commit 32
commit 33
commit 34
commit 35
commit 36
commit 37
commit 38
commit 39
commit 40
commit 41
commit 42
commit 43
commit 44
commit 45
commit 46
commit 47
commit 48
commit 49
commit 50
commit 51
commit 52
commit 53
commit 54
commit 55
commit 56
commit 57
commit 58
commit 59
commit 60
commit 61
commit 62
commit 63
commit 64
commit 65
commit 66
commit 67
commit 68
commit 69
commit 70
commit 71
commit 72
commit 73
commit 74
commit 75
commit 76
commit 77
commit 78
commit 79
commit 80
commit 81
commit 82
commit 83
commit 84
commit 85
commit 86
commit 87
