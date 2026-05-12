# moziazou3.github.io
export default function CarteVisiteElectronique() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-slate-900 via-slate-800 to-slate-900 flex items-center justify-center p-6">
      <div className="w-full max-w-md bg-white rounded-3xl shadow-2xl overflow-hidden border border-slate-200">
        <div className="bg-gradient-to-r from-blue-600 to-cyan-500 p-8 text-white text-center">
          <div className="w-24 h-24 mx-auto rounded-full bg-white/20 backdrop-blur flex items-center justify-center text-4xl font-bold border border-white/30">
            IT
          </div>
          <h1 className="mt-4 text-3xl font-bold">Ziadi Mohamed</h1>
          <p className="text-blue-100 mt-2 text-lg">Consultant IT Genesys</p>
        </div>

        <div className="p-8 space-y-5">
          <div className="flex items-center gap-4 bg-slate-50 rounded-2xl p-4 hover:bg-slate-100 transition">
            <div className="text-2xl">📧</div>
            <div>
              <p className="text-sm text-slate-500">Email</p>
              <p className="font-medium text-slate-800">zizioud.mohamed@yahoo.com</p>
            </div>
          </div>

          <div className="flex items-center gap-4 bg-slate-50 rounded-2xl p-4 hover:bg-slate-100 transition">
            <div className="text-2xl">📱</div>
            <div>
              <p className="text-sm text-slate-500">Téléphone</p>
              <p className="font-medium text-slate-800">06 10 10 10 10</p>
            </div>
          </div>

          <div className="flex items-center gap-4 bg-slate-50 rounded-2xl p-4 hover:bg-slate-100 transition">
            <div className="text-2xl">🌐</div>
            <div>
              <p className="text-sm text-slate-500">Site Web</p>
              <p className="font-medium text-slate-800">Freelance • Rouen</p>
            </div>
          </div>

          <div className="flex items-center gap-4 bg-slate-50 rounded-2xl p-4 hover:bg-slate-100 transition">
            <div className="text-2xl">💼</div>
            <div>
              <p className="text-sm text-slate-500">Spécialités</p>
              <p className="font-medium text-slate-800">
                Genesys • Centre de contact • Cloud • CX
              </p>
            </div>
          </div>

          <div className="flex flex-col items-center justify-center pt-2">
            <div className="bg-white border border-slate-200 rounded-2xl p-4 shadow-sm">
              <img
                src="https://api.qrserver.com/v1/create-qr-code/?size=180x180&data=BEGIN:VCARD%0AVERSION:3.0%0AN:Mohamed;Ziadi%0AFN:Ziadi Mohamed%0AORG:Freelance%0ATITLE:Consultant IT Genesys%0ATEL:0610101010%0AEMAIL:zizioud.mohamed@yahoo.com%0AADR:;;Rouen;;;;France%0AEND:VCARD"
                alt="QR Code"
                className="w-40 h-40 rounded-xl"
              />
            </div>
            <p className="text-sm text-slate-500 mt-3 text-center">
              Scannez pour enregistrer mes coordonnées
            </p>
          </div>

          <div className="pt-4">
            <button className="w-full bg-gradient-to-r from-blue-600 to-cyan-500 text-white py-4 rounded-2xl font-semibold text-lg shadow-lg hover:scale-[1.02] transition-transform">
              Voir ma fiche en ligne
            </button>
          </div>
        </div>
      </div>
    </div>
  );
}
