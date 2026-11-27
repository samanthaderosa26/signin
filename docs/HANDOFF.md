# Open house sign-in: how to use it

Everything runs on your own Google and GitHub accounts. You never need to
touch code. There are two places you'll use:

- **Your admin page.** This is the bookmark ending in `/exec`. Open it on your
  phone or laptop while signed in to your Google account.
- **Your Google Sheet, "Open House Sign-ins".** It's in your Google Drive and
  has three tabs: **Houses**, **SignIns** and **Settings**.

> **Tip:** If the admin page says "Sorry, unable to open the file", more than
> one Google account is signed in to that browser. Open the bookmark in a
> private/incognito window and sign in with just your account.

## Add a house

1. Open your admin page.
2. Under **New open house**, fill in the **Address** (required). Price, beds,
   baths, square feet, a short description and the listing link are optional,
   but guests will see whatever you enter.
3. Tap **Save and make QR code**. You'll see "QR code ready" with that
   house's QR code.

Every house gets its own QR code, so sign-ins are always matched to the right
address.

## Print a QR code

1. On the admin page, tap **Print QR**. It's shown right after you add a
   house, or next to any house under **Past open houses**.
2. Tap **Print**. Use letter paper, portrait.
3. In the print options, turn off **Headers and footers** so only the QR code
   and logo print. You can also choose **Save as PDF** and print it later.
4. Before the open house, scan the printed code with your phone camera to
   make sure it opens the sign-in form for the right house.

Tap **Back** to return to the admin page.

**To turn off a house's QR code** after the open house, open the **Houses**
tab in your Sheet and untick that house's **active** box. Tick it again to
turn it back on.

## Find sign-ins

- **Right away:** every sign-in sends you an email with the subject
  **"Open House Sign-in: (guest name) — (address)"** and all of their answers.
  Reply to that email to write straight back to the guest.
- **All of them:** open the **SignIns** tab in your Sheet. Each row is one
  guest, with the date, the house, their contact info and answers. Use
  **Data → Create a filter** to sort by house or date.
- Guests also get a thank-you email from your Gmail automatically.

If you download the sign-ins as a file, don't open it in Excel with macros
turned on.

**Gmail tip:** search for `subject:"Open House Sign-in:"`, then click the
filter icon → **Create filter** → **Apply the label** "Open House" and tick
**Never send it to Spam**. Turn on notifications for that label in the Gmail
app to get a ping for every sign-in.

## Change the website URL

After guests sign in, they're sent to your website. The thank-you email's
**Learn more about me** button goes there too.

1. Open your Sheet and go to the **Settings** tab.
2. Find the row **website_url** and paste the new address in column B. It
   must start with `https://`.

That's it. The change takes effect right away, and your printed QR codes keep
working.

The other rows in **Settings** work the same way: your name, title, phone,
email and office address for the email signature, and **notify_email** if you
want sign-in alerts sent to a different inbox. Column C explains each one.
Don't change **guest_form_url**, because your QR codes depend on it.

## Good to know

- Your Gmail can send about 100 emails a day from the sign-in system. Each
  sign-in uses up to two (your alert and the guest's thank-you). On a very
  busy day, the thank-you emails pause first so your alerts keep coming. Every
  sign-in is always saved in the Sheet, even if an email is skipped.
- Nothing here costs money, and nothing runs on anyone else's computer.
