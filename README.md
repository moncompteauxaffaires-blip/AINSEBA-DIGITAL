# AINSEBA-DIGITAL

**[Voir le dépôt sur GitHub](https://github.com/moncompteauxaffaires-blip/AINSEBA-DIGITAL)**

https://moncompteauxaffaires-blip.github.io/AINSEBA-DIGITAL/

export default function Home() {
  return (
    <div className="min-h-screen bg-white text-gray-900">
      {/* Hero */}
      <section className="bg-black text-white py-24">
        <div className="max-w-6xl mx-auto px-6">
          <h1 className="text-5xl font-bold mb-6">
            Ainseba Digital
          </h1>

          <p className="text-xl max-w-2xl mb-8">
            Agence digitale spécialisée dans la création de sites web
            modernes, rapides et optimisés pour convertir vos visiteurs en
            clients.
          </p>

          <div className="flex gap-4">
            <a
              href="#contact"
              className="bg-blue-600 hover:bg-blue-700 px-6 py-3 rounded-lg"
            >
              Demander un devis
            </a>

            <a
              href="#projects"
              className="border border-white px-6 py-3 rounded-lg"
            >
              Voir nos réalisations
            </a>
          </div>
        </div>
      </section>

      {/* Services */}
      <section className="py-20">
        <div className="max-w-6xl mx-auto px-6">
          <h2 className="text-4xl font-bold text-center mb-14">
            Nos Services
          </h2>

          <div className="grid md:grid-cols-3 gap-8">
            <div className="shadow-lg p-6 rounded-xl">
              <h3 className="text-2xl font-semibold mb-4">
                Création de Sites Web
              </h3>

              <p>
                Sites vitrines modernes, rapides et adaptés à tous les
                appareils.
              </p>
            </div>

            <div className="shadow-lg p-6 rounded-xl">
              <h3 className="text-2xl font-semibold mb-4">
                Référencement SEO
              </h3>

              <p>
                Optimisation pour améliorer votre visibilité sur Google.
              </p>
            </div>

            <div className="shadow-lg p-6 rounded-xl">
              <h3 className="text-2xl font-semibold mb-4">
                Maintenance
              </h3>

              <p>
                Mises à jour, sécurité et accompagnement continu.
              </p>
            </div>
          </div>
        </div>
      </section>

      {/* Réalisations */}
      <section id="projects" className="bg-gray-100 py-20">
        <div className="max-w-6xl mx-auto px-6">
          <h2 className="text-4xl font-bold text-center mb-14">
            Réalisations
          </h2>

          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-white rounded-xl shadow-lg overflow-hidden">
              <img
                src="/project1.jpg"
                alt="Projet"
                className="w-full h-52 object-cover"
              />

              <div className="p-6">
                <h3 className="text-xl font-semibold">
                  Site Vitrine Restaurant
                </h3>

                <p className="mt-2 text-gray-600">
                  Site moderne optimisé mobile et SEO.
                </p>
              </div>
            </div>

            <div className="bg-white rounded-xl shadow-lg overflow-hidden">
              <img
                src="/project2.jpg"
                alt="Projet"
                className="w-full h-52 object-cover"
              />

              <div className="p-6">
                <h3 className="text-xl font-semibold">
                  Portfolio Développeur
                </h3>

                <p className="mt-2 text-gray-600">
                  Présentation professionnelle des compétences et projets.
                </p>
              </div>
            </div>

            <div className="bg-white rounded-xl shadow-lg overflow-hidden">
              <img
                src="/project3.jpg"
                alt="Projet"
                className="w-full h-52 object-cover"
              />

              <div className="p-6">
                <h3 className="text-xl font-semibold">
                  Ainseba Digital
                </h3>

                <p className="mt-2 text-gray-600">
                  Plateforme officielle de l'agence digitale.
                </p>
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* CTA */}
      <section className="bg-blue-600 text-white py-20">
        <div className="max-w-4xl mx-auto text-center px-6">
          <h2 className="text-4xl font-bold mb-6">
            Prêt à lancer votre projet ?
          </h2>

          <p className="mb-8">
            Discutons ensemble de votre futur site web.
          </p>

          <a
            href="#contact"
            className="bg-white text-blue-600 px-8 py-3 rounded-lg font-semibold"
          >
            Contactez-nous
          </a>
        </div>
      </section>

      {/* Contact */}
      <section id="contact" className="py-20">
        <div className="max-w-3xl mx-auto px-6">
          <h2 className="text-4xl font-bold text-center mb-10">
            Contact
          </h2>

          <form className="space-y-4">
            <input
              type="text"
              placeholder="Nom"
              className="w-full border p-3 rounded-lg"
            />

            <input
              type="email"
              placeholder="Email"
              className="w-full border p-3 rounded-lg"
            />

            <textarea
              placeholder="Votre message"
              rows="6"
              className="w-full border p-3 rounded-lg"
            />

            <button
              className="bg-black text-white px-6 py-3 rounded-lg"
              type="submit"
            >
              Envoyer
            </button>
          </form>
        </div>
      </section>
    </div>
  );
}
