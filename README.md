# DIAS DAS MAES
...
export default function MothersDaySite(){return (<div className='min-h-screen bg-gradient-to-b from-pink-100 via-rose-50 to-white text-gray-800 font-sans'>

  <section className='min-h-screen flex flex-col items-center justify-center px-6 text-center'>
    <div className='text-6xl mb-4'>💐</div>
    <h1 className='text-5xl md:text-7xl font-bold mb-4'>Feliz Dia das Mães</h1>
    <p className='max-w-2xl text-lg md:text-2xl text-gray-600 mb-8'>Um espaço feito para celebrar amor, carinho e tudo que uma mãe representa.</p>
    <a href='#mensagem' className='px-8 py-4 bg-rose-500 text-white rounded-2xl shadow-lg hover:scale-105 transition'>Ver homenagem</a>
  </section>
  <section id='mensagem' className='py-20 px-6'>
    <div className='max-w-4xl mx-auto grid md:grid-cols-2 gap-8'>
      <div className='bg-white rounded-3xl shadow-xl p-8'>
        <h2 className='text-3xl font-semibold mb-4'>Uma mensagem especial</h2>
        <p className='leading-8 text-lg'>Mãe, obrigado por cada conselho, cada abraço e por nunca desistir. Sua força inspira, seu cuidado acolhe e seu amor transforma tudo ao redor.</p>
      </div>
      <div className='bg-rose-100 rounded-3xl shadow-xl p-8 flex items-center justify-center text-center'>
        <div>
          <div className='text-6xl mb-4'>❤️</div>
          <p className='text-2xl font-medium'>Você é meu maior presente.</p>
        </div>
      </div>
    </div>
  </section>
  <section className='py-20 px-6 bg-rose-50'>
    <h2 className='text-4xl font-bold text-center mb-10'>Motivos para agradecer</h2>
    <div className='max-w-5xl mx-auto grid md:grid-cols-3 gap-6'>
      {['Amor incondicional','Cuidado diário','Força e inspiração'].map((item,i)=>(<div key={i} className='bg-white p-6 rounded-2xl shadow-md text-center text-xl'>{item}</div>))}
    </div>
  </section>
  <footer className='py-10 text-center text-gray-500'>Feito com carinho para o Dia das Mães 🌷</footer>
</div>)}
