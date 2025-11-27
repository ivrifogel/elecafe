import React, { useState, useEffect } from 'react';
import { Coffee, MapPin, Clock, Phone, Menu as MenuIcon, X, Instagram, Facebook, Twitter, Heart, Users, Utensils, Wifi, Sun } from 'lucide-react';

// --- Custom Styles for Animations ---
const animationStyles = `
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translate3d(0, 20px, 0);
    }
    to {
      opacity: 1;
      transform: translate3d(0, 0, 0);
    }
  }

  .animate-fade-in-up {
    animation: fadeInUp 0.8s ease-out forwards;
  }
  
  .delay-100 { animation-delay: 0.1s; }
  .delay-200 { animation-delay: 0.2s; }
  .delay-300 { animation-delay: 0.3s; }
`;

// --- Components ---

// 1. Navigation Bar
const Navbar = ({ activeTab, setActiveTab, isMobileMenuOpen, setIsMobileMenuOpen }) => {
  const navLinks = [
    { name: 'Home', id: 'home' },
    { name: 'Menu', id: 'menu' },
    { name: 'Our Story', id: 'story' },
    { name: 'Contact', id: 'contact' },
  ];

  return (
    <nav className="bg-stone-900 text-stone-50 fixed w-full z-50 shadow-lg transition-all duration-300">
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div className="flex justify-between items-center h-20">
          {/* Logo Area */}
          <div 
            className="flex-shrink-0 flex items-center cursor-pointer group" 
            onClick={() => setActiveTab('home')}
          >
            <div className="w-10 h-10 bg-amber-700 rounded-full flex items-center justify-center mr-3 shadow-md border-2 border-amber-600/20 group-hover:bg-amber-600 transition-colors">
              <Coffee className="text-amber-100 w-5 h-5" />
            </div>
            <div className="flex flex-col">
              <h1 className="text-lg font-bold tracking-widest font-serif leading-none text-amber-50">MELRICHES</h1>
              <span className="text-[10px] font-medium tracking-[0.2em] text-amber-500 font-serif uppercase">Coffeehouse</span>
            </div>
          </div>

          {/* Desktop Menu */}
          <div className="hidden md:flex space-x-8">
            {navLinks.map((link) => (
              <button
                key={link.id}
                onClick={() => setActiveTab(link.id)}
                className={`text-xs font-bold uppercase tracking-[0.15em] transition-all duration-300 py-2 border-b-2 ${
                  activeTab === link.id ? 'text-amber-500 border-amber-500' : 'text-stone-400 border-transparent hover:text-white hover:border-stone-600'
                }`}
              >
                {link.name}
              </button>
            ))}
          </div>

          {/* Mobile Menu Button */}
          <div className="md:hidden flex items-center">
            <button
              onClick={() => setIsMobileMenuOpen(!isMobileMenuOpen)}
              className="text-stone-300 hover:text-amber-500 focus:outline-none transition-colors"
            >
              {isMobileMenuOpen ? <X className="w-6 h-6" /> : <MenuIcon className="w-6 h-6" />}
            </button>
          </div>
        </div>
      </div>

      {/* Mobile Menu Dropdown */}
      {isMobileMenuOpen && (
        <div className="md:hidden bg-stone-900 border-t border-stone-800 absolute w-full shadow-xl">
          <div className="px-4 pt-4 pb-6 space-y-2">
            {navLinks.map((link) => (
              <button
                key={link.id}
                onClick={() => {
                  setActiveTab(link.id);
                  setIsMobileMenuOpen(false);
                }}
                className={`block w-full text-left px-4 py-3 rounded text-sm font-bold uppercase tracking-widest ${
                  activeTab === link.id ? 'bg-stone-800 text-amber-500' : 'text-stone-400 hover:bg-stone-800 hover:text-white'
                }`}
              >
                {link.name}
              </button>
            ))}
          </div>
        </div>
      )}
    </nav>
  );
};

// 2. Hero Section
const Hero = ({ setActiveTab }) => (
  <div className="relative bg-stone-900 h-[80vh] min-h-[500px] flex items-center justify-center text-center px-4 overflow-hidden">
    {/* Background Image Overlay */}
    <div className="absolute inset-0 z-0">
      <div className="absolute inset-0 bg-black/60 z-10" /> {/* Darker overlay for better text contrast */}
      <img 
        src="https://images.unsplash.com/photo-1497935586351-b67a49e012bf?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80" 
        alt="Melriches Coffeehouse Atmosphere" 
        className="w-full h-full object-cover animate-fade-in-up scale-105 transition-transform duration-[30s] ease-linear hover:scale-110"
      />
    </div>
    
    <div className="relative z-20 max-w-4xl mx-auto opacity-0 animate-fade-in-up delay-100">
      <h2 className="text-amber-400 text-xs md:text-sm font-bold tracking-[0.3em] uppercase mb-4">
        Davie Village • Est. 1997
      </h2>
      <h1 className="text-4xl md:text-7xl font-serif font-bold text-white mb-6 leading-tight drop-shadow-2xl">
        Make That Happy <br/> <span className="text-amber-500">Connection</span>
      </h1>
      <p className="text-stone-200 text-base md:text-xl mb-10 max-w-2xl mx-auto font-light leading-relaxed">
        An independent coffeehouse where neighbors become friends. No corporate mandates, just good coffee and real community.
      </p>
      <div className="flex flex-col sm:flex-row gap-4 justify-center">
        <button 
          onClick={() => setActiveTab('menu')}
          className="px-8 py-3 bg-amber-700 text-white text-xs font-bold uppercase tracking-widest hover:bg-amber-600 transition-all shadow-lg rounded-sm"
        >
          Our Menu
        </button>
        <button 
          onClick={() => setActiveTab('contact')}
          className="px-8 py-3 bg-transparent border border-stone-300 text-stone-100 text-xs font-bold uppercase tracking-widest hover:bg-white hover:text-stone-900 hover:border-white transition-all rounded-sm"
        >
          Find Us
        </button>
      </div>
    </div>
  </div>
);

// 3. Features Section (Reformatted: Clean Icon Row)
const Features = () => (
  <section className="py-16 bg-white border-b border-stone-100">
    <div className="max-w-6xl mx-auto px-6">
      <div className="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
        
        <div className="group opacity-0 animate-fade-in-up delay-100">
          <div className="w-12 h-12 mx-auto mb-4 flex items-center justify-center rounded-full bg-amber-50 text-amber-700 group-hover:bg-amber-700 group-hover:text-white transition-all duration-300">
            <Users className="w-6 h-6" />
          </div>
          <h3 className="font-bold text-stone-900 text-sm uppercase tracking-wide mb-2">Community Focused</h3>
          <p className="text-xs text-stone-500 leading-relaxed max-w-[150px] mx-auto">
            A hub for locals to meet and connect.
          </p>
        </div>

        <div className="group opacity-0 animate-fade-in-up delay-200">
          <div className="w-12 h-12 mx-auto mb-4 flex items-center justify-center rounded-full bg-amber-50 text-amber-700 group-hover:bg-amber-700 group-hover:text-white transition-all duration-300">
            <Heart className="w-6 h-6" />
          </div>
          <h3 className="font-bold text-stone-900 text-sm uppercase tracking-wide mb-2">Independent Spirit</h3>
          <p className="text-xs text-stone-500 leading-relaxed max-w-[150px] mx-auto">
            Decisions made here, not in a boardroom.
          </p>
        </div>

        <div className="group opacity-0 animate-fade-in-up delay-300">
          <div className="w-12 h-12 mx-auto mb-4 flex items-center justify-center rounded-full bg-amber-50 text-amber-700 group-hover:bg-amber-700 group-hover:text-white transition-all duration-300">
            <Utensils className="w-6 h-6" />
          </div>
          <h3 className="font-bold text-stone-900 text-sm uppercase tracking-wide mb-2">House Baking</h3>
          <p className="text-xs text-stone-500 leading-relaxed max-w-[150px] mx-auto">
            Cookies, soups & sandwiches made daily.
          </p>
        </div>

        <div className="group opacity-0 animate-fade-in-up delay-300">
          <div className="w-12 h-12 mx-auto mb-4 flex items-center justify-center rounded-full bg-amber-50 text-amber-700 group-hover:bg-amber-700 group-hover:text-white transition-all duration-300">
            <Wifi className="w-6 h-6" />
          </div>
          <h3 className="font-bold text-stone-900 text-sm uppercase tracking-wide mb-2">Laptop Friendly</h3>
          <p className="text-xs text-stone-500 leading-relaxed max-w-[150px] mx-auto">
            Free WiFi and plenty of power outlets.
          </p>
        </div>

      </div>
    </div>
  </section>
);

// 4. Menu Section (Reformatted: Compact List)
const Menu = () => {
  const categories = [
    {
      title: "Espresso",
      items: [
        { name: "House Latte", desc: "Rich espresso, velvety milk", price: "5.50" },
        { name: "Cappuccino", desc: "Equal parts espresso, milk, foam", price: "5.25" },
        { name: "Americano", desc: "Espresso, hot water", price: "4.50" },
        { name: "Mocha", desc: "Espresso, chocolate, milk", price: "6.00" },
      ]
    },
    {
      title: "Bakery",
      items: [
        { name: "Ginger Molasses Cookie", desc: "Chewy, spicy house favorite", price: "3.50" },
        { name: "Daily Muffin", desc: "Blueberry, Bran, or Morning Glory", price: "4.00" },
        { name: "Butter Croissant", desc: "Baked fresh daily", price: "4.25" },
        { name: "GF Brownie", desc: "Flourless chocolate fudge", price: "4.50" },
      ]
    },
    {
      title: "Lunch",
      items: [
        { name: "Tuna Melt", desc: "Cheddar, sourdough, grilled", price: "12.50" },
        { name: "Turkey Pesto", desc: "Roasted turkey, provolone", price: "13.00" },
        { name: "Avocado Toast", desc: "Chili flakes, lemon, multigrain", price: "10.50" },
        { name: "Daily Soup", desc: "Scratch made. Ask for feature.", price: "8.00" },
      ]
    }
  ];

  return (
    <div className="bg-stone-50 pt-28 pb-16 min-h-screen opacity-0 animate-fade-in-up">
      <div className="max-w-4xl mx-auto px-4">
        <div className="text-center mb-12">
          <h2 className="text-amber-700 font-bold tracking-widest uppercase text-xs mb-2">Fresh & Local</h2>
          <h1 className="text-3xl md:text-4xl font-serif font-bold text-stone-900">Current Menu</h1>
        </div>

        <div className="grid md:grid-cols-2 gap-8">
            {categories.map((cat, index) => (
                <div key={index} className={`bg-white p-6 rounded-lg shadow-sm border border-stone-100 ${index === 2 ? 'md:col-span-2 md:w-2/3 md:mx-auto' : ''}`}>
                    <h3 className="text-xl font-serif font-bold text-stone-800 mb-4 pb-2 border-b border-stone-100 flex items-center text-amber-700">
                        {cat.title}
                    </h3>
                    <ul className="space-y-4">
                        {cat.items.map((item, idx) => (
                        <li key={idx} className="flex justify-between items-end group">
                            <div className="w-full">
                                <div className="flex justify-between items-baseline w-full border-b border-stone-100 pb-1 mb-1 border-dotted">
                                    <h4 className="text-sm font-bold text-stone-700 uppercase tracking-wide">{item.name}</h4>
                                    <span className="text-stone-900 font-serif font-medium">{item.price}</span>
                                </div>
                                <p className="text-xs text-stone-500 italic">{item.desc}</p>
                            </div>
                        </li>
                        ))}
                    </ul>
                </div>
            ))}
        </div>
        
        <div className="mt-12 text-center">
            <p className="text-xs text-stone-400 uppercase tracking-widest">Menu items subject to seasonal availability</p>
        </div>
      </div>
    </div>
  );
};

// 5. Our Story Section (Reformatted: Compact)
const OurStory = () => (
  <div className="bg-white pt-28 pb-16 opacity-0 animate-fade-in-up">
    <div className="max-w-4xl mx-auto px-6">
      <div className="flex flex-col md:flex-row gap-10 items-start">
        {/* Image - Smaller now */}
        <div className="md:w-1/3">
          <img 
            src="https://images.unsplash.com/photo-1554118811-1e0d58224f24?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" 
            alt="Cafe Interior" 
            className="rounded shadow-md w-full h-auto object-cover grayscale hover:grayscale-0 transition-all duration-500"
          />
        </div>
        
        {/* Text - Tighter */}
        <div className="md:w-2/3">
          <h2 className="text-amber-700 font-bold tracking-widest uppercase text-xs mb-2">Est. 1997</h2>
          <h1 className="text-3xl font-serif font-bold text-stone-900 mb-4">Davie Village Roots</h1>
          <div className="space-y-4 text-stone-600 text-sm leading-relaxed">
            <p>
              The original Melriches Coffeehouse began trading on Davie Street in 1997. While the West End has changed, our mission remains simple: <strong>build community.</strong>
            </p>
            <p>
              We are proudly anti-franchise. Our furniture doesn't match, our playlist is eclectic, and our decisions are made right here. We believe success isn't just about the bottom line—it's about connecting one person to another.
            </p>
            <div className="border-l-2 border-amber-500 pl-4 py-1 my-4 bg-stone-50">
                <p className="font-serif text-stone-800 italic text-sm">
                "Shyness is nice, but shyness can stop you from saying all the things in life you'd like to."
                </p>
            </div>
            <p>
              Come in, pull up a chair by the window, and say hello. It's your cafe, after all.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
);

// 6. Contact Section (Reformatted: Compact)
const Contact = () => (
  <div className="bg-stone-50 pt-28 pb-16 opacity-0 animate-fade-in-up min-h-screen">
    <div className="max-w-5xl mx-auto px-6">
      <div className="grid md:grid-cols-2 gap-8">
        
        {/* Info Column */}
        <div className="space-y-6">
            <div>
                <h1 className="text-3xl font-serif font-bold text-stone-900 mb-6">Visit Us</h1>
                
                <div className="bg-white p-6 rounded shadow-sm border border-stone-100 space-y-6">
                    <div className="flex items-start gap-4">
                        <MapPin className="w-5 h-5 text-amber-600 mt-1 flex-shrink-0" />
                        <div>
                            <h3 className="font-bold text-stone-800 text-sm uppercase mb-1">Location</h3>
                            <p className="text-stone-600 text-sm">1244 Davie Street<br/>Vancouver, BC V6E 1N4</p>
                        </div>
                    </div>

                    <div className="flex items-start gap-4">
                        <Clock className="w-5 h-5 text-amber-600 mt-1 flex-shrink-0" />
                        <div className="w-full">
                            <h3 className="font-bold text-stone-800 text-sm uppercase mb-1">Hours</h3>
                            <div className="text-stone-600 text-sm flex justify-between w-full max-w-[200px]">
                                <span>Mon-Fri</span> <span>6:30am – 6:30pm</span>
                            </div>
                            <div className="text-stone-600 text-sm flex justify-between w-full max-w-[200px]">
                                <span>Sat-Sun</span> <span>7:00am – 6:30pm</span>
                            </div>
                        </div>
                    </div>

                    <div className="flex items-start gap-4">
                        <Phone className="w-5 h-5 text-amber-600 mt-1 flex-shrink-0" />
                        <div>
                            <h3 className="font-bold text-stone-800 text-sm uppercase mb-1">Contact</h3>
                            <p className="text-stone-600 text-sm"><a href="tel:+16046895282" className="hover:text-amber-600">+1 604 689 5282</a></p>
                            <p className="text-stone-600 text-sm"><a href="mailto:info@melriches.com" className="hover:text-amber-600">info@melriches.com</a></p>
                        </div>
                    </div>
                </div>
            </div>

            {/* Socials */}
            <div className="flex gap-4">
                <a href="https://twitter.com/melriches" target="_blank" rel="noreferrer" className="flex items-center justify-center w-10 h-10 bg-white border border-stone-200 rounded-full hover:bg-amber-50 hover:border-amber-200 hover:text-amber-600 transition-all">
                    <Twitter className="w-4 h-4" />
                </a>
                <a href="https://www.facebook.com/pages/Melriches-Coffeehouse/137110499634957" target="_blank" rel="noreferrer" className="flex items-center justify-center w-10 h-10 bg-white border border-stone-200 rounded-full hover:bg-amber-50 hover:border-amber-200 hover:text-amber-600 transition-all">
                    <Facebook className="w-4 h-4" />
                </a>
                <a href="#" className="flex items-center justify-center w-10 h-10 bg-white border border-stone-200 rounded-full hover:bg-amber-50 hover:border-amber-200 hover:text-amber-600 transition-all">
                    <Instagram className="w-4 h-4" />
                </a>
            </div>
        </div>

        {/* Map Embed - Adjusted height */}
        <div className="h-64 md:h-auto bg-stone-200 rounded overflow-hidden border border-stone-300 shadow-sm relative min-h-[300px]">
            <iframe 
                src="https://maps.google.com/maps?q=1244+Davie+St,+Vancouver,+BC&t=&z=15&ie=UTF8&iwloc=&output=embed"
                width="100%" 
                height="100%" 
                style={{border:0}} 
                allowFullScreen="" 
                loading="lazy" 
                title="Melriches Coffeehouse Location"
                className="grayscale hover:grayscale-0 transition-all duration-500 absolute inset-0"
            ></iframe>
        </div>

      </div>
    </div>
  </div>
);

// 7. Footer
const Footer = ({ setActiveTab }) => (
  <footer className="bg-stone-900 text-stone-500 py-12 border-t border-stone-800">
    <div className="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
      <div className="mb-6 md:mb-0 text-center md:text-left">
        <h2 className="text-sm font-bold text-stone-300 font-serif tracking-wider uppercase">Melriches Coffeehouse</h2>
        <p className="text-xs mt-2 opacity-50">© {new Date().getFullYear()} All rights reserved.</p>
      </div>
      
      <div className="flex gap-6 text-center">
        <button onClick={() => setActiveTab('home')} className="hover:text-amber-500 transition-colors text-xs uppercase tracking-widest">Home</button>
        <button onClick={() => setActiveTab('menu')} className="hover:text-amber-500 transition-colors text-xs uppercase tracking-widest">Menu</button>
        <button onClick={() => setActiveTab('story')} className="hover:text-amber-500 transition-colors text-xs uppercase tracking-widest">Story</button>
        <button onClick={() => setActiveTab('contact')} className="hover:text-amber-500 transition-colors text-xs uppercase tracking-widest">Contact</button>
      </div>
    </div>
  </footer>
);

// --- Main App Component ---

const App = () => {
  const [activeTab, setActiveTab] = useState('home');
  const [isMobileMenuOpen, setIsMobileMenuOpen] = useState(false);

  useEffect(() => {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }, [activeTab]);

  return (
    <div className="font-sans antialiased text-stone-900 bg-stone-50 min-h-screen flex flex-col selection:bg-amber-200 selection:text-amber-900">
      <style>{animationStyles}</style>
      <Navbar 
        activeTab={activeTab} 
        setActiveTab={setActiveTab} 
        isMobileMenuOpen={isMobileMenuOpen} 
        setIsMobileMenuOpen={setIsMobileMenuOpen} 
      />

      {/* Content Area */}
      <main className="flex-grow">
        {activeTab === 'home' && (
          <>
            <Hero setActiveTab={setActiveTab} />
            <Features />
            <div className="bg-amber-50 py-16 text-center px-6 opacity-0 animate-fade-in-up">
                <div className="max-w-2xl mx-auto">
                    <h3 className="text-2xl font-bold font-serif text-stone-900 mb-3">Community Coffee Table</h3>
                    <p className="text-stone-600 text-sm leading-relaxed mb-6">
                        Every week we host community tables where neighbors chat over coffee. 
                        Perfect for breaking the ice or just enjoying good company.
                    </p>
                    <button onClick={() => setActiveTab('contact')} className="text-amber-700 text-xs font-bold uppercase tracking-widest border-b border-amber-700 hover:text-amber-900 hover:border-amber-900 transition-colors pb-1">
                        Join Us
                    </button>
                </div>
            </div>
          </>
        )}

        {activeTab === 'menu' && <Menu />}
        {activeTab === 'story' && <OurStory />}
        {activeTab === 'contact' && <Contact />}
      </main>

      <Footer setActiveTab={setActiveTab} />
    </div>
  );
};

export default App;
