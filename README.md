<!-- PROJECT LOGO -->
<p align="center">

  <h3 align="center">Cal.com (formerly Calendso)</h3>

  <p align="center">
    The open-source Calendly successor.
    <br />
    <a href="https://cal.com"><strong>Learn more »</strong></a>
    <br />
</p>


<!-- ABOUT THE PROJECT -->

## About the Project

# Scheduling infrastructure for absolutely everyone

The open source Calendly successor. You are in charge
of your own data, workflow, and appearance.

Calendly and other scheduling tools are awesome. It made our lives massively easier. We're using it for business meetings, seminars, yoga classes, and even calls with our families. However, most tools are very limited in terms of control and customization.

That's where Cal.com comes in. Self-hosted or hosted by us. White-label by design. API-driven and ready to be deployed on your own domain. Full control of your events and data.

## Recognition

### Built With

- [Next.js](https://nextjs.org/?ref=cal.com)
- [tRPC](https://trpc.io/?ref=cal.com)
- [React.js](https://reactjs.org/?ref=cal.com)
- [Tailwind CSS](https://tailwindcss.com/?ref=cal.com)
- [Prisma.io](https://prisma.io/?ref=cal.com)
- [Daily.co](https://go.cal.com/daily)

## Contact us

Meet our sales team for any commercial inquiries.

<a href="https://cal.com/sales"><img src="https://cal.com/book-with-cal-dark.svg" alt="Book us with Cal.com"></a>


<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running, please follow these simple steps.

### Prerequisites

Here is what you need to be able to run Cal.com.

- Node.js (Version: >=18.x)
- PostgreSQL (Version: >=13.x)
- Yarn _(recommended)_

> If you want to enable any of the available integrations, you may want to obtain additional credentials for each one. More details on this can be found below under the [integrations section](#integrations).

## Development

## Deployment

### Docker

The Docker configuration for Cal.com is an effort powered by people within the community.

If you want to contribute to the Docker repository, [reply here](https://github.com/calcom/docker/discussions/32).

The Docker configuration can be found [in our docker repository](https://github.com/calcom/docker).

Issues with Docker? Find your answer or open a new discussion [here](https://github.com/calcom/docker/discussions) to ask the community.

Cal.com, Inc. does not provide official support for Docker, but we will accept fixes and documentation. Use at your own risk.

### Railway

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/cal)

You can deploy Cal.com on [Railway](https://railway.app) using the button above. The team at Railway also have a [detailed blog post](https://blog.railway.app/p/calendso) on deploying Cal.com on their platform.

### Vercel

Currently Vercel Pro Plan is required to be able to Deploy this application with Vercel, due to limitations on the number of serverless functions on the free plan.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fcalcom%2Fcal.com&env=DATABASE_URL,NEXT_PUBLIC_WEBAPP_URL,NEXTAUTH_URL,NEXTAUTH_SECRET,CRON_API_KEY,CALENDSO_ENCRYPTION_KEY&envDescription=See%20all%20available%20env%20vars&envLink=https%3A%2F%2Fgithub.com%2Fcalcom%2Fcal.com%2Fblob%2Fmain%2F.env.example&project-name=cal&repo-name=cal.com&build-command=cd%20../..%20%26%26%20yarn%20build&root-directory=apps%2Fweb%2F)

### Render

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy?repo=https://github.com/calcom/docker)

### Elestio

[![Deploy on Elestio](https://elest.io/images/logos/deploy-to-elestio-btn.png)](https://elest.io/open-source/cal.com)

<!-- ROADMAP -->

## Roadmap

<a href="https://cal.com/roadmap"><img src="https://user-images.githubusercontent.com/8019099/176388295-25081ca4-207e-4468-8079-37b195fa8e59.png" alt="Cal.com Roadmap" /></a>

See the [roadmap project](https://cal.com/roadmap) for a list of proposed features (and known issues). You can change the view to see planned tagged releases.

<!-- LICENSE -->

## License

Cal.com, Inc. is a commercial open source company, which means some parts of this open source repository require a commercial license. The concept is called "Open Core" where the core technology (99%) is fully open source, licensed under [AGPLv3](https://opensource.org/license/agpl-v3) and the last 1% is covered under a commercial license (["/ee" Enterprise Edition](https://github.com/calcom/cal.com/tree/main/packages/features/ee)) which we believe is entirely relevant for larger organisations that require enterprise features. Enterprise features are built by the core engineering team of Cal.com, Inc. which is hired in full-time. Find their compensation on https://cal.com/open.

> [!NOTE]  
> Our philosophy is simple, all "Singleplayer APIs" are open-source under AGPLv3. All commercial "Multiplayer APIs" are under a commercial license.


> [!TIP]
> We work closely with the community and always invite feedback about what should be open and what is fine to be commercial. This list is not set and stone and we have moved things from commercial to open in the past. Please open a [discussion] if you feel like something is wrong.

## Repo Activity

<img width="100%" src="https://repobeats.axiom.co/api/embed/6bfca2f20f39738048b6e70ca205efde46352c3d.svg" />

<!-- CONTRIBUTING -->

## Contributing

Please see our [contributing guide](/CONTRIBUTING.md).

### Good First Issues

We have a list of help wanted that contain small features and bugs which have a relatively limited scope. This is a great place to get started, gain experience, and get familiar with our contribution process.


### Translations

Don't code but still want to contribute? Join our Discussions and join the #Translate channel and let us know what language you want to translate.

![ar translation](https://img.shields.io/badge/dynamic/json?color=blue&label=ar&style=flat&logo=crowdin&query=%24.progress.0.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![bg translation](https://img.shields.io/badge/dynamic/json?color=blue&label=bg&style=flat&logo=crowdin&query=%24.progress.1.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![cs translation](https://img.shields.io/badge/dynamic/json?color=blue&label=cs&style=flat&logo=crowdin&query=%24.progress.2.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![de translation](https://img.shields.io/badge/dynamic/json?color=blue&label=de&style=flat&logo=crowdin&query=%24.progress.3.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![el translation](https://img.shields.io/badge/dynamic/json?color=blue&label=el&style=flat&logo=crowdin&query=%24.progress.4.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![en translation](https://img.shields.io/badge/dynamic/json?color=blue&label=en&style=flat&logo=crowdin&query=%24.progress.5.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![es translation](https://img.shields.io/badge/dynamic/json?color=blue&label=es&style=flat&logo=crowdin&query=%24.progress.6.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![es-419 translation](https://img.shields.io/badge/dynamic/json?color=blue&label=es-419&style=flat&logo=crowdin&query=%24.progress.7.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![fr translation](https://img.shields.io/badge/dynamic/json?color=blue&label=fr&style=flat&logo=crowdin&query=%24.progress.8.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![he translation](https://img.shields.io/badge/dynamic/json?color=blue&label=he&style=flat&logo=crowdin&query=%24.progress.9.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![hu translation](https://img.shields.io/badge/dynamic/json?color=blue&label=hu&style=flat&logo=crowdin&query=%24.progress.10.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![it translation](https://img.shields.io/badge/dynamic/json?color=blue&label=it&style=flat&logo=crowdin&query=%24.progress.11.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![ja translation](https://img.shields.io/badge/dynamic/json?color=blue&label=ja&style=flat&logo=crowdin&query=%24.progress.12.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![ko translation](https://img.shields.io/badge/dynamic/json?color=blue&label=ko&style=flat&logo=crowdin&query=%24.progress.13.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![nl translation](https://img.shields.io/badge/dynamic/json?color=blue&label=nl&style=flat&logo=crowdin&query=%24.progress.14.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![no translation](https://img.shields.io/badge/dynamic/json?color=blue&label=no&style=flat&logo=crowdin&query=%24.progress.15.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![pl translation](https://img.shields.io/badge/dynamic/json?color=blue&label=pl&style=flat&logo=crowdin&query=%24.progress.16.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![pt translation](https://img.shields.io/badge/dynamic/json?color=blue&label=pt&style=flat&logo=crowdin&query=%24.progress.17.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![pt-BR translation](https://img.shields.io/badge/dynamic/json?color=blue&label=pt-BR&style=flat&logo=crowdin&query=%24.progress.18.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![ro translation](https://img.shields.io/badge/dynamic/json?color=blue&label=ro&style=flat&logo=crowdin&query=%24.progress.19.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![ru translation](https://img.shields.io/badge/dynamic/json?color=blue&label=ru&style=flat&logo=crowdin&query=%24.progress.20.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![sr translation](https://img.shields.io/badge/dynamic/json?color=blue&label=sr&style=flat&logo=crowdin&query=%24.progress.21.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![sv translation](https://img.shields.io/badge/dynamic/json?color=blue&label=sv&style=flat&logo=crowdin&query=%24.progress.22.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![tr translation](https://img.shields.io/badge/dynamic/json?color=blue&label=tr&style=flat&logo=crowdin&query=%24.progress.23.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![uk translation](https://img.shields.io/badge/dynamic/json?color=blue&label=uk&style=flat&logo=crowdin&query=%24.progress.24.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![vi translation](https://img.shields.io/badge/dynamic/json?color=blue&label=vi&style=flat&logo=crowdin&query=%24.progress.25.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![zh-CN translation](https://img.shields.io/badge/dynamic/json?color=blue&label=zh-CN&style=flat&logo=crowdin&query=%24.progress.26.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json) ![zh-TW translation](https://img.shields.io/badge/dynamic/json?color=blue&label=zh-TW&style=flat&logo=crowdin&query=%24.progress.27.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-200011276-1.json)

## Enabling Content Security Policy

- Set CSP_POLICY="non-strict" env variable, which enables Strict CSP except for unsafe-inline in style-src . If you have some custom changes in your instance, you might have to make some code change to make your instance CSP compatible. Right now it enables strict CSP only on login page and on other SSR pages it is enabled in Report only mode to detect possible issues. On, SSG pages it is still not supported.

## Integrations

### Obtaining the Google API Credentials

1. Open Google API Console. If you don't have a project in your Google Cloud subscription, you'll need to create one before proceeding further. Under Dashboard pane, select Enable APIS and Services.
2. In the search box, type calendar and select the Google Calendar API search result.
3. Enable the selected API.
4. Next, go to the OAuth consent screen from the side pane. Select the app type (Internal or External) and enter the basic app details on the first page.
5. In the second page on Scopes, select Add or Remove Scopes. Search for Calendar.event and select the scope with scope value `.../auth/calendar.events`, `.../auth/calendar.readonly` and select Update.
6. In the third page (Test Users), add the Google account(s) you'll be using. Make sure the details are correct on the last page of the wizard and your consent screen will be configured.
7. Now select Credentials from the side pane and then select Create Credentials. Select the OAuth Client ID option.
8. Select Web Application as the Application Type.
9. Under Authorized redirect URI's, select Add URI and then add the URI `<Cal.com URL>/api/integrations/googlecalendar/callback` and `<Cal.com URL>/api/auth/callback/google` replacing Cal.com URL with the URI at which your application runs.
10. The key will be created and you will be redirected back to the Credentials page. Select the newly generated client ID under OAuth 2.0 Client IDs.
11. Select Download JSON. Copy the contents of this file and paste the entire JSON string in the `.env` file as the value for `GOOGLE_API_CREDENTIALS` key.

#### _Adding google calendar to Cal.com App Store_

After adding Google credentials, you can now Google Calendar App to the app store.
You can repopulate the App store by running

```
cd packages/prisma
yarn seed-app-store
```

You will need to complete a few more steps to activate Google Calendar App.
Make sure to complete section "Obtaining the Google API Credentials". After that do the
following

1. Add extra redirect URL `<Cal.com URL>/api/auth/callback/google`
1. Under 'OAuth consent screen', click "PUBLISH APP"

### Obtaining Microsoft Graph Client ID and Secret

1. Open Azure App Registration and select New registration
2. Name your application
3. Set **Who can use this application or access this API?** to **Accounts in any organizational directory (Any Azure AD directory - Multitenant)**
4. Set the **Web** redirect URI to `<Cal.com URL>/api/integrations/office365calendar/callback` replacing Cal.com URL with the URI at which your application runs.
5. Use **Application (client) ID** as the **MS_GRAPH_CLIENT_ID** attribute value in .env
6. Click **Certificates & secrets** create a new client secret and use the value as the **MS_GRAPH_CLIENT_SECRET** attribute

### Obtaining Zoom Client ID and Secret

1. Open Zoom Marketplace and sign in with your Zoom account.
2. On the upper right, click "Develop" => "Build App".
3. Select "General App" , click "Create".
4. Name your App.
5. Choose "User-managed app" for "Select how the app is managed".
6. De-select the option to publish the app on the Zoom App Marketplace, if asked.
7. Now copy the Client ID and Client Secret to your `.env` file into the `ZOOM_CLIENT_ID` and `ZOOM_CLIENT_SECRET` fields.
8. Set the "OAuth Redirect URL" under "OAuth Information" as `<Cal.com URL>/api/integrations/zoomvideo/callback` replacing Cal.com URL with the URI at which your application runs.
9. Also add the redirect URL given above as an allow list URL and enable "Subdomain check". Make sure, it says "saved" below the form.
10. You don't need to provide basic information about your app. Instead click on "Scopes" and then on "+ Add Scopes". On the left,
    1. click the category "Meeting" and check the scope `meeting:write:meeting`.
    2. click the category "User" and check the scope `user:read:settings`.
11. Click "Done".
12. You're good to go. Now you can easily add your Zoom integration in the Cal.com settings.

### Obtaining Daily API Credentials

1. Visit our Daily.co Partnership Form and enter your information
2. From within your dashboard, go to the developerstab.
3. Copy your API key.
4. Now paste the API key to your `.env` file into the `DAILY_API_KEY` field in your `.env` file.
5. If you have the [Daily Scale Plan](https://daily.co/pricing) set the `DAILY_SCALE_PLAN` variable to `true` in order to use features like video recording.

### Obtaining Basecamp Client ID and Secret

1. Visit the [37 Signals Integrations Dashboard](launchpad.37signals.com/integrations) and sign in.
2. Register a new application by clicking the Register one now link.
3. Fill in your company details.
4. Select Basecamp 4 as the product to integrate with.
5. Set the Redirect URL for OAuth `<Cal.com URL>/api/integrations/basecamp3/callback` replacing Cal.com URL with the URI at which your application runs.
6. Click on done and copy the Client ID and secret into the `BASECAMP3_CLIENT_ID` and `BASECAMP3_CLIENT_SECRET` fields.
7. Set the `BASECAMP3_CLIENT_SECRET` env variable to `{your_domain} ({support_email})`.
   For example, `Cal.com (support@cal.com)`.

### Obtaining HubSpot Client ID and Secret

1. Open [HubSpot Developer](https://developer.hubspot.com/) and sign into your account, or create a new one.
2. From within the home of the Developer account page, go to "Manage apps".
3. Click "Create app" button top right.
4. Fill in any information you want in the "App info" tab
5. Go to tab "Auth"
6. Now copy the Client ID and Client Secret to your `.env` file into the `HUBSPOT_CLIENT_ID` and `HUBSPOT_CLIENT_SECRET` fields.
7. Set the Redirect URL for OAuth `<Cal.com URL>/api/integrations/hubspot/callback` replacing Cal.com URL with the URI at which your application runs.
8. In the "Scopes" section at the bottom of the page, make sure you select "Read" and "Write" for scope called `crm.objects.contacts`
9. Click the "Save" button at the bottom footer.
10. You're good to go. Now you can see any booking in Cal.com created as a meeting in HubSpot for your contacts.

### Obtaining ZohoCRM Client ID and Secret

1. Open [Zoho API Console](https://api-console.zoho.com/) and sign into your account, or create a new one.
2. From within the API console page, go to "Applications".
3. Click "ADD CLIENT" button top right and select "Server-based Applications".
4. Fill in any information you want in the "Client Details" tab
5. Go to tab "Client Secret" tab.
6. Now copy the Client ID and Client Secret to your `.env` file into the `ZOHOCRM_CLIENT_ID` and `ZOHOCRM_CLIENT_SECRET` fields.
7. Set the Redirect URL for OAuth `<Cal.com URL>/api/integrations/zohocrm/callback` replacing Cal.com URL with the URI at which your application runs.
8. In the "Settings" section check the "Multi-DC" option if you wish to use the same OAuth credentials for all data centers.
9. Click the "Save"/ "UPDATE" button at the bottom footer.
10. You're good to go. Now you can easily add your ZohoCRM integration in the Cal.com settings.

## Workflows

### Setting up SendGrid for Email reminders

1. Create a SendGrid account (https://signup.sendgrid.com/)
2. Go to Settings -> API keys and create an API key
3. Copy API key to your `.env` file into the `SENDGRID_API_KEY` field
4. Go to Settings -> Sender Authentication and verify a single sender
5. Copy the verified E-Mail to your `.env` file into the `SENDGRID_EMAIL` field
6. Add your custom sender name to the `.env` file into the `NEXT_PUBLIC_SENDGRID_SENDER_NAME` field (fallback is Cal.com)

### Setting up Twilio for SMS reminders

1. Create a Twilio account (https://twilio.com/try-twilio)
2. Click ‘Get a Twilio phone number’
3. Copy Account SID to your `.env` file into the `TWILIO_SID` field
4. Copy Auth Token to your `.env` file into the `TWILIO_TOKEN` field
5. Copy your Twilio phone number to your `.env` file into the `TWILIO_PHONE_NUMBER` field
6. Add your own sender ID to the `.env` file into the `NEXT_PUBLIC_SENDER_ID` field (fallback is Cal.com)
7. Create a messaging service (Develop -> Messaging -> Services)
8. Choose any name for the messaging service
9. Click 'Add Senders'
10. Choose phone number as sender type
11. Add the listed phone number
12. Leave all other fields as they are
13. Complete setup and click ‘View my new Messaging Service’
14. Copy Messaging Service SID to your `.env` file into the `TWILIO_MESSAGING_SID` field
15. Create a verify service
16. Copy Verify Service SID to your `.env` file into the `TWILIO_VERIFY_SID` field


<!-- ACKNOWLEDGEMENTS -->

## Acknowledgements

Special thanks to these amazing projects which help power Cal.com:

- [Vercel](https://vercel.com/?utm_source=calend-so&utm_campaign=oss)
- [Next.js](https://nextjs.org/)
- [Day.js](https://day.js.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Prisma](https://prisma.io/)

Cal.com is an open startup and [Jitsu](https://github.com/jitsucom/jitsu) (an open-source Segment alternative) helps us to track most of the usage metrics.
