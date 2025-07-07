# Test1
ChatGPT Generated Website Code
import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { YoutubeIcon, Music, Mail } from "lucide-react";

export default function RareHymnsSite() { return ( <div className="min-h-screen bg-gradient-to-b from-white to-yellow-100 p-6"> <header className="text-center py-10"> <h1 className="text-4xl font-bold text-yellow-800">Rare Hymns</h1> <p className="text-lg mt-2 text-yellow-700"> Enjoy uplifting and satisfying hymns from the Rare Hymns Channel. </p> <a
href="https://youtube.com/@rarehymnschannel6424?si=Lf0lXmMlVA0QJqzX"
target="_blank"
rel="noopener noreferrer"
> <Button className="mt-4 bg-yellow-700 hover:bg-yellow-800 text-white"> <YoutubeIcon className="mr-2" /> Visit YouTube Channel </Button> </a> </header>

<main className="grid grid-cols-1 md:grid-cols-2 gap-6 max-w-5xl mx-auto">
    <Card className="shadow-xl border-yellow-300">
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold text-yellow-800 mb-2">
          🎵 What We Offer
        </h2>
        <p className="text-yellow-700">
          Rare hymns that touch the soul, inspire faith, and bring peace to the heart. Discover both familiar classics and hidden gems.
        </p>
      </CardContent>
    </Card>

    <Card className="shadow-xl border-yellow-300">
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold text-yellow-800 mb-2">
          📌 Why Subscribe?
        </h2>
        <p className="text-yellow-700">
          Stay updated with regularly posted hymns, perfect for worship, relaxation, or quiet reflection. Let the music lift your spirit.
        </p>
      </CardContent>
    </Card>

    <Card className="shadow-xl border-yellow-300 md:col-span-2">
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold text-yellow-800 mb-2">
          🎥 Latest Hymn Video
        </h2>
        <div className="aspect-w-16 aspect-h-9">
          <iframe
            className="w-full h-64 md:h-96 rounded-xl"
            src="https://www.youtube.com/embed?listType=user_uploads&list=rarehymnschannel6424"
            title="Rare Hymns YouTube Video"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowFullScreen
          ></iframe>
        </div>
      </CardContent>
    </Card>

    <Card className="shadow-xl border-yellow-300 md:col-span-2">
      <CardContent className="p-6">
        <h2 className="text-xl font-semibold text-yellow-800 mb-2">
          📬 Contact Us
        </h2>
        <form className="grid gap-4">
          <input
            type="text"
            placeholder="Your Name"
            className="p-2 border border-yellow-400 rounded"
          />
          <input
            type="email"
            placeholder="Your Email"
            className="p-2 border border-yellow-400 rounded"
          />
          <textarea
            rows="4"
            placeholder="Your Message"
            className="p-2 border border-yellow-400 rounded"
          ></textarea>
          <Button className="bg-yellow-700 hover:bg-yellow-800 text-white">
            <Mail className="mr-2" /> Send Message
          </Button>
        </form>
      </CardContent>
    </Card>
  </main>

  <footer className="text-center mt-10 text-yellow-600">
    © 2025 Rare Hymns Channel. All rights reserved.
  </footer>
</div>

); }

