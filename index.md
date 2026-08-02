# Privacy Policy for AlloHrayfi

*Last updated: 27 July 2026*

AlloHrayfi ("we", "our", "us") operates the AlloHrayfi mobile application (the "App"), also referred to as Hrayfiya — a service marketplace connecting customers with local service providers in Morocco. This policy explains what we collect, why, and what control you have.

See also our [Terms of Service](terms.html).

## Information We Collect

- **Account information:** email address, name, phone number, date of birth, city, and profile photo
- **Location data:** precise location (with your permission) to show service providers near you and to set the address for a booking. Service providers who list a shop location share that location publicly in the App
- **Camera and photos:** used only when you choose to take a profile or shop photo, send an image in chat, or scan a booking QR code
- **Storage access:** to select and upload images from your device
- **Messages:** chat messages and images exchanged between customers and service providers
- **Bookings and ratings:** service bookings, addresses used, booking history, and the ratings you leave
- **Device information:** a push notification token, used to deliver booking and chat alerts
- **Language preference:** so notifications reach you in the language you use

We do not collect payment card details. Payment for services is made in cash directly between the customer and the service provider.

## How We Use Your Information

- Match customers with nearby service providers and operate bookings
- Enable in-app chat between customers and providers
- Send booking updates and message notifications
- Display ratings and reviews
- Investigate reports of abuse and enforce our [Terms of Service](terms.html)
- Provide customer support and improve the App

## Permissions We Request

| Permission | iOS key | Why |
|---|---|---|
| Camera | `NSCameraUsageDescription` | Profile and shop photos; scanning booking QR codes |
| Photo Library | `NSPhotoLibraryUsageDescription` | Uploading images from your device |
| Location (When In Use) | `NSLocationWhenInUseUsageDescription` | Finding nearby providers; setting a booking address |
| Notifications | — | Booking and chat alerts |

On Android these correspond to `CAMERA`, `READ/WRITE_EXTERNAL_STORAGE`, and `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION`.

All permissions require your explicit consent, and every one is optional. You can revoke any of them at any time in your device settings; some features will not work without them.

## Where Your Data Is Stored

We use the following service providers to operate the App:

- **Supabase** — hosts the database, accounts, and chat messages. Data is encrypted in transit over HTTPS and protected by row-level security rules
- **Cloudflare R2** — stores images you upload (profile pictures, shop photos, and photos sent in chat). Uploads pass through our upload service hosted on Vercel
- **Expo Push Notification Service** — delivers push notifications to your device
- **Google Maps** — renders maps and resolves addresses

## Data Sharing

**We do not sell your personal data, and we do not share it with third parties for advertising.** Information is shared only:

- Between a customer and the service provider they book with (name, phone number, booking address, and messages)
- With the infrastructure providers listed above, strictly to run the App
- When required by law, or to investigate fraud, abuse, or a threat to someone's safety

Your profile name, photo, service type, ratings, and shop location are visible to other users of the App.

## Data Retention

We keep your data for as long as your account exists. When you delete your account, your profile, bookings, messages, addresses, favourites, ratings, and push token are permanently removed.

Reports of abuse may be retained for a limited period where needed to keep the platform safe or to meet a legal obligation.

## Your Rights

You can:

- **Access and correct** your information from the Profile screen in the App
- **Delete your account** at any time from **Settings → Delete account**. This is immediate and permanent
- **Request a copy** of your data, or ask a question about this policy, by emailing us
- **Withdraw permissions** for location, camera, photos, or notifications in your device settings

## Security

Access to data is enforced at the database level with row-level security, so users can only read their own bookings, messages, and addresses. All network traffic uses HTTPS. No system is perfectly secure, and we cannot guarantee absolute security.

## Children's Privacy

AlloHrayfi is not directed at children and is not intended for anyone under 13. We do not knowingly collect personal information from children under 13. If you believe a child has given us personal information, contact us and we will delete it.

## Changes to This Policy

We may update this policy from time to time. The "last updated" date above will change, and material changes will be announced in the App.

## Contact

For any privacy question or request: **hhrayfiya@gmail.com**
