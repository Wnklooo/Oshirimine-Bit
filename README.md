import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { motion } from "framer-motion";

export default function Home() {
  return (
    <div className="min-h-screen bg-gray-900 text-white p-4">
      <header className="text-center py-10">
        <h1 className="text-4xl font-bold">Oshiriminebit</h1>
        <p className="text-lg mt-2">Minería de Bitcoin Autosustentable en Atacama</p>
      </header>
      
      <section className="grid grid-cols-1 md:grid-cols-2 gap-6">
        <Card>
          <CardContent>
            <h2 className="text-2xl font-semibold">¿Qué es Oshiriminebit?</h2>
            <p className="mt-2">Oshiriminebit es un proyecto innovador que busca minar Bitcoin utilizando energía solar en la región de Atacama, aprovechando su alta radiación solar y baja competencia.</p>
          </CardContent>
        </Card>
        <Card>
          <CardContent>
            <h2 className="text-2xl font-semibold">¿Cómo funciona?</h2>
            <p className="mt-2">Mediante el uso de paneles solares y equipos ASIC de última generación, se extraen Bitcoins de forma eficiente y sostenible.</p>
          </CardContent>
        </Card>
      </section>

      <section className="mt-10">
        <h2 className="text-3xl font-bold text-center">Estrategia de Negocio</h2>
        <div className="grid grid-cols-1 md:grid-cols-3 gap-6 mt-6">
          <Card>
            <CardContent>
              <h3 className="text-xl font-semibold">Minería Propia</h3>
              <p className="mt-2">Granjas autosustentables con energía solar y reinversión en expansión.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="text-xl font-semibold">Venta de ASICs</h3>
              <p className="mt-2">Comercialización de equipos y red compartida para mineros individuales.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="text-xl font-semibold">Energía Verde</h3>
              <p className="mt-2">Venta de energía renovable y desarrollo de iluminación sostenible.</p>
            </CardContent>
          </Card>
        </div>
      </section>
      
      <section className="mt-10 text-center">
        <h2 className="text-3xl font-bold">Inversión y Rentabilidad</h2>
        <p className="mt-4">Con una inversión inicial entre $500,000 y $1,000,000 USD, se pueden generar hasta $16,000 USD diarios con una operación escalada.</p>
        <Button className="mt-4 bg-green-500 text-white px-6 py-2 rounded-lg">Conoce más</Button>
      </section>

      <section className="mt-10">
        <h2 className="text-3xl font-bold text-center">Impacto Regional</h2>
        <p className="text-center mt-4">Generación de empleo, atracción de inversión y fomento del uso de criptomonedas en Atacama.</p>
      </section>

      <section className="mt-10">
        <h2 className="text-3xl font-bold text-center">Preguntas Frecuentes</h2>
        <div className="mt-6 space-y-4">
          <Card>
            <CardContent>
              <h3 className="text-xl font-semibold">¿Es rentable minar Bitcoin en Atacama?</h3>
              <p className="mt-2">Sí, gracias a la energía solar, los costos operativos son bajos y la rentabilidad es alta.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="text-xl font-semibold">¿Cómo puedo invertir en el proyecto?</h3>
              <p className="mt-2">Puedes invertir directamente en ASICs o en infraestructura a través de nuestros programas de inversión.</p>
            </CardContent>
          </Card>
          <Card>
            <CardContent>
              <h3 className="text-xl font-semibold">¿Cuáles son los riesgos?</h3>
              <p className="mt-2">El Bitcoin es volátil, pero con energía autosustentable se minimizan los riesgos operativos.</p>
            </CardContent>
          </Card>
        </div>
      </section>

      <section className="mt-10 text-center">
        <h2 className="text-3xl font-bold">Contáctanos</h2>
        <form className="mt-6 max-w-lg mx-auto bg-gray-800 p-6 rounded-lg">
          <input type="text" placeholder="Nombre" className="w-full p-2 mb-4 rounded bg-gray-700 text-white" />
          <input type="email" placeholder="Correo Electrónico" className="w-full p-2 mb-4 rounded bg-gray-700 text-white" />
          <textarea placeholder="Mensaje" className="w-full p-2 mb-4 rounded bg-gray-700 text-white" rows="4"></textarea>
          <Button className="bg-green-500 text-white px-6 py-2 rounded-lg">Enviar</Button>
        </form>
      </section>

      <footer className="text-center mt-10 py-6 border-t border-gray-700">
        <p>&copy; 2025 Oshiriminebit. Todos los derechos reservados.</p>
      </footer>
    </div>
  );
}
