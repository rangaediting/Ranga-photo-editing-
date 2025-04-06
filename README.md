# Ranga-photo-editing-
Photo editing 
import React from "react"; import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button";

export default function RangaPhotoEditing() { return ( <main className="p-6 space-y-6 bg-gradient-to-br from-purple-100 to-white min-h-screen"> <header className="text-center space-y-2"> <h1 className="text-4xl font-bold text-purple-700">Ranga Photo Editing</h1> <p className="text-lg text-gray-600"> Premium Photo Editing Services – Ramini Jaisi AI Photo & More (मराठी / English) </p> </header>

<section className="grid md:grid-cols-3 gap-6">
    <Card>
      <CardContent className="p-4">
        <h2 className="text-xl font-semibold text-purple-600">फोटो एडिटिंग सेवा</h2>
        <p className="text-gray-700 mt-2">
          आम्ही विविध प्रकारचे फोटो एडिटिंग करतो – रंग सुधारणा, पार्श्वभूमी बदल, रिटचिंग इत्यादी.
        </p>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-4">
        <h2 className="text-xl font-semibold text-purple-600">Ramini Jaisi AI फोटो</h2>
        <p className="text-gray-700 mt-2">
          एआय वापरून तुमचे फोटो रामिणी सारखे सुंदर बनवा – खास मराठी टचसह.
        </p>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-4">
        <h2 className="text-xl font-semibold text-purple-600">Contact / संपर्क करा</h2>
        <p className="text-gray-700 mt-2">
          तुमच्या फोटोसाठी आजच संपर्क करा – आम्ही लवकरात लवकर सेवा देतो.
        </p>
        <Button className="mt-4">संपर्क फॉर्म</Button>
      </CardContent>
    </Card>
  </section>
</main>

); }

