# ATA-pro-am
import "./globals.css";
import Navbar from "../components/Navbar";

export const metadata = {
  title: "ATA",
  description: "Pro-Am Stat Tracker",
};

export default function RootLayout({
  children,
}: {
  children: React.ReactNode;
}) {
  return (
    <html lang="en">
      <body>
        <Navbar />
        {children}
      </body>
    </html>
  );
}
