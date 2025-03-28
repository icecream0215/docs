# Manage Serverless Endpoints

Learn how to effectively manage Serverless Endpoints.

## Create an Endpoint

You can create an Endpoint using the Web interface.

1. Go to [Serverless Endpoints](https://submodel.ai/#/serverless/list).
2. Click on **+ New Endpoint** and provide the following details:
   1. **Endpoint Name**.
   2. **Select your GPUs**.
   3. **Configure your workers**.
   4. **Add a container image**.
   5. Click **Deploy**.

## Delete an Endpoint

You can delete an Endpoint via the Web interface.
Ensure all workers are removed before deleting an Endpoint.

1. Visit [Serverless Endpoints](https://submodel.ai/#/serverless/list).
2. Choose the Endpoint you wish to delete.
3. Click **Edit Endpoint** and set **Max Workers** to `0`.
4. Click **Update** and then **Delete Endpoint**.

## Edit an Endpoint

You can modify a running Endpoint through the Web interface after deployment.

1. Access [Serverless Endpoints](https://submodel.ai/#/serverless/list).
2. Select the Endpoint you want to edit.
3. Click **Edit Endpoint**, make the necessary changes.
4. Click **Update**.

## Set GPU Prioritization for an Endpoint

When creating or modifying a Worker Endpoint, specify your GPU preferences in order of priority.
This configuration allows you to select preferred GPU models for your Worker Endpoints.

SubModel will attempt to allocate your top choice if available.
If the preferred GPU is unavailable, the system will automatically switch to the next available GPU in your list.

1. Go to [Serverless Endpoints](https://submodel.ai/#/serverless/list).
2. Choose the Endpoint you wish to update.
3. Set the priority for the GPUs you prefer.
4. Click **Update**.



**To force a configuration update:**

- Set **Max Workers** to `0`.
- Click **Update**.
- Adjust your **Max Workers** back to the desired value.

