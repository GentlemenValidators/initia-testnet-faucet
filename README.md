## Configuration Files Setup

1. **Environment Variables**
   Copy the example environment variables file to create your own `.env` file.
Edit the port you want it to run on.

2. **Blockchain Networks Configuration**
Copy the example chains configuration to set up your network specifics.
Add chains / mnemonics you want to use. On start, you can view addresses via `http://ip:port/<chain_id>`.

## Running the Faucet

### Local Environment

To run the faucet in a local development environment, use the following command:

### Production Environment

For production deployment, install `pm2` and use it to manage the application process.

1. **Install PM2**

2. **Start the Faucet**

3. **PM2 Utilities**
- To view logs:
  ```
  pm2 logs
  ```
- To stop the faucet:
  ```
  pm2 stop faucet
  ```
