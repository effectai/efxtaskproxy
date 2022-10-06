# efxtaskproxy

Effect Network efxtaskproxy repository for Non Effect controllerd dApps

[Efxtaskproxy](https://app.effect.network/profile/efxtaskproxy) is an Effect Network controlled account that let's anyone to post a task to it's campaign. This is useful for campaigns that want to have tasks are bought by the community.

Let's sketch it out a bit, you've managed to your dApp added to the ecosystem. But now what's left? You need to get people to use your dApp and buy tasks from it.  
But in order to have anyone buy a task from your dApp and post it to a campaign you need to use the efxtaskproxy account.  
This account is controlled by the Effect Network team and is used to post tasks to campaigns.  

In order to do these actions your dApp needs to be able to call these following two actions: `force.efx::mkbatch` and `force.efx::posttask`

This is easy if you are owner of the campaign and you want to post tasks to it. But it is not possible if you are not the owner of the campaign.

That's why we've created the efxtaskproxy account. It's permissions are set up in such a way that you're dApp can post any task that your dApp creates from anyone at anytime.

Build your Campaign as you normally would on [Testnet](https://testnet.effect.network) and then submit a pull request to add your campaign to the efxtaskproxy account.

- First build your campaign on [Testnet](https://testnet.effect.network)
- After you've finished testing it go to your Task page, and click `Edit Task` button.
- You should be able to see the `exort` button in upper right corner of the page, click it.
- Go to [Github.com/effectai/efxtaskproxy](https://github.com/effectai/efxtaskproxy)
- Fork the repository
- Add the `exort` output to the forked repository
- Commit your changes and make a new pull request.

We'll review your PR, merge it if everything looks good and we'll upload it for you to the efxtaskproxy account.
Please allow us one business day to review your PR and merge it.
