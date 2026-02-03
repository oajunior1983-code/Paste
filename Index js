export default function Home() {
  return (
    <div style={{ fontFamily: "Arial, sans-serif", padding: 20 }}>
      
      <header style={{ maxWidth: 1100, margin: "0 auto 40px" }}>
        <h1>OAJ3D Designers</h1>
        <p>Loja online completa de filamentos 3D e tintas para impressoras</p>
        <p>📍 Rua Carmelita Gama Romeiro, 299 – Pindamonhangaba / SP</p>
        <p>
          💬 <a href="https://wa.me/5512982384591">WhatsApp: (12) 98238-4591</a>
        </p>
      </header>

      <main
        style={{
          maxWidth: 1100,
          margin: "0 auto",
          display: "grid",
          gridTemplateColumns: "repeat(auto-fit, minmax(250px, 1fr))",
          gap: 20,
        }}
      >
        {/* PRODUTO 1 */}
        <div style={cardStyle}>
          <h2>Filamento PLA Premium</h2>
          <p>Ideal para impressões detalhadas</p>
          <strong>R$ 89,90</strong>
          <button
            style={buttonStyle}
            onClick={() =>
              window.location.href =
                "COLE_AQUI_LINK_MERCADO_PAGO"
            }
          >
            Comprar agora
          </button>
        </div>

        {/* PRODUTO 2 */}
        <div style={cardStyle}>
          <h2>Filamento ABS Profissional</h2>
          <p>Alta resistência térmica</p>
          <strong>R$ 99,90</strong>
          <button
            style={buttonStyle}
            onClick={() =>
              window.location.href =
                "COLE_AQUI_LINK_MERCADO_PAGO"
            }
          >
            Comprar agora
          </button>
        </div>

        {/* PRODUTO 3 */}
        <div style={cardStyle}>
          <h2>Tinta Compatível Premium</h2>
          <p>Alto rendimento e cores vivas</p>
          <strong>R$ 39,90</strong>
          <button
            style={buttonStyle}
            onClick={() =>
              window.location.href =
                "COLE_AQUI_LINK_MERCADO_PAGO"
            }
          >
            Comprar agora
          </button>
        </div>
      </main>

      <footer style={{ textAlign: "center", marginTop: 40 }}>
        <p>💳 Pagamentos aceitos: Pix • Cartão • Boleto</p>
        <p>© 2026 OAJ3D Designers</p>
      </footer>

      {/* WhatsApp flutuante */}
      <a
        href="https://wa.me/5512982384591"
        style={whatsStyle}
      >
        💬 WhatsApp
      </a>
    </div>
  );
}

const cardStyle = {
  border: "1px solid #ddd",
  borderRadius: 8,
  padding: 20,
};

const buttonStyle = {
  marginTop: 10,
  padding: "10px 15px",
  backgroundColor: "#16a34a",
  color: "#fff",
  border: "none",
  borderRadius: 5,
  cursor: "pointer",
};

const whatsStyle = {
  position: "fixed",
  bottom: 20,
  right: 20,
  backgroundColor: "#16a34a",
  color: "#fff",
  padding: "12px 18px",
  borderRadius: 30,
  textDecoration: "none",
  fontWeight: "bold",
};
