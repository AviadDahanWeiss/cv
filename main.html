import React, { useState, useEffect, useMemo } from 'react';
import { 
  Briefcase, 
  GraduationCap, 
  Award, 
  Mail, 
  Phone, 
  Linkedin, 
  TrendingUp, 
  Database, 
  Layers,
  Calendar,
  ChevronDown,
  ChevronUp,
  X,
  ExternalLink,
  Printer,
  Moon,
  Sun,
  Download,
  MapPin,
  Copy,
  Check
} from 'lucide-react';

// --- Assets & Data ---

const profile = {
  name: "Aviad Dahan-Weiss",
  role: "FP&A Director",
  initials: "AD",
  contact: {
    phone: "+972-53-336-36-52",
    email: "Aviad.Dahan.Weiss@gmail.com",
    linkedin: "https://www.linkedin.com/in/aviaddahanweiss",
    location: "Israel"
  },
  summary: "Experienced FP&A Director with 10 years of expertise in budgeting, forecasting, P&L management, cash flow analysis, and KPI reporting. A trusted partner to CEOs and CFOs, delivering strategic insights and innovative financial solutions.",
  highlights: [
    { label: "Experience", value: "10 Years", icon: Calendar, isInteractive: true, type: "experience" },
    { label: "Strategic Impact", value: "C-Level Partner", icon: TrendingUp }, 
    { label: "Team Leadership", value: "6+ Analysts", icon: Briefcase },
    { label: "Systems", value: "14+ Tools", icon: Database, isInteractive: true, type: "systems" },
  ]
};

const experience = [
  {
    id: 1,
    role: "FP&A Director",
    company: "Fireblocks",
    type: "SaaS",
    period: "2023 - Present",
    description: "First and sole FP&A leader in the Israeli site, partnering with co-founders and C-level executives.",
    achievements: [
      "Established standardized budgeting, forecasting, and control processes.",
      "Built a data model to measure cost efficiencies of blockchains.",
      "Developed a process for analyzing the P&L at the product level.",
      "Collaborated with FinOps on cloud costs, reporting, and efficiency strategies."
    ]
  },
  {
    id: 2,
    role: "Senior Finance Director",
    company: "Bizzabo",
    type: "SaaS",
    period: "2022 - 2023",
    description: "Led AP and FP&A teams, streamlining financial operations and directing annual budget preparation.",
    achievements: [
      "Built dynamic data models to facilitate revenue and expense forecasting.",
      "Partnered with LOB leaders to monitor actuals and identify improvements.",
      "Automated financial processes, reducing reporting timelines.",
      "Managed financial systems: NetSuite, Mesh, and Tipalti."
    ]
  },
  {
    id: 3,
    role: "FP&A Director",
    company: "Ex Libris",
    type: "SaaS",
    period: "2017 - 2022",
    note: "Promoted from Analyst → Team Leader → Manager → Director",
    description: "Managed a team of six analysts supporting 10 business units globally. Reported directly to CEO.",
    achievements: [
      "Delivered monthly P&L reports and built a BI dashboard from scratch.",
      "Implemented systems like Planful, Coupa, Concur, and Salesforce CPQ.",
      "Developed and deployed a budget control tool using VBA, Power Query, and Power BI.",
      "Led the NetSuite ERP improvement project, streamlining financial processes."
    ]
  },
  {
    id: 4,
    role: "Manager of Financial Dept. & Chief Economist",
    company: "Moriah",
    type: "Jerusalem Development Co.",
    period: "2015 - 2017",
    note: "Rapid Progression: Economist → Chief Economist → Dept. Manager",
    description: "Managed a multi-year budget of NIS 6.5B and an annual budget of NIS 750M. Led a team of economists to achieve financial objectives.",
    achievements: [
      "Conducted financial feasibility studies and implemented a BI system.",
      "Collaborated with municipal bodies to ensure budget compliance.",
      "Oversaw month-end closings, including reconciliations and forex reporting.",
      "Delivered detailed analyses to support management decisions."
    ]
  }
];

const education = [
  {
    degree: "Master of Arts in Economics",
    school: "The Hebrew University of Jerusalem",
    year: "2015 - 2018",
    link: "https://economics.huji.ac.il/en"
  },
  {
    degree: "B.A. Philosophy, Economics, & Political Science",
    school: "The Hebrew University of Jerusalem",
    year: "2012 - 2015",
    link: "https://pep.huji.ac.il/"
  }
];

const skillsDetail = [
  { 
    category: "ERP & Finance", 
    items: [
      { name: "NetSuite", domain: "netsuite.com" },
      { name: "Planful", domain: "planful.com" },
      { name: "Adaptive", domain: "workday.com" },
      { name: "Coupa", domain: "coupa.com" },
      { name: "Tipalti", domain: "tipalti.com" },
      { name: "Mesh", domain: "meshpayments.com" },
      { name: "Concur", domain: "concur.com" }
    ]
  },
  { 
    category: "Data & BI", 
    items: [
      { name: "Excel", domain: "microsoft.com" },
      { name: "Power BI", domain: "powerbi.microsoft.com" },
      { name: "Power Query", domain: "microsoft.com" },
      { name: "VBA", domain: "microsoft.com" },
    ]
  },
  { 
    category: "HR & Ops", 
    items: [
      { name: "Salesforce", domain: "salesforce.com" },
      { name: "Comeet", domain: "comeet.com" },
      { name: "UltiPto", domain: "ukg.com" },
      { name: "HiBob", domain: "hibob.com" }
    ]
  }
];

// --- Components ---

const Avatar = ({ src, alt, initials }: { src: string, alt: string, initials: string }) => {
  const [error, setError] = useState(false);
  
  if (error || !src) {
    return (
      <div className="w-full h-full bg-slate-100 dark:bg-slate-800 flex flex-col items-center justify-center text-slate-400 dark:text-slate-500 border-2 border-dashed border-slate-300 dark:border-slate-600">
        <span className="text-2xl font-bold">{initials}</span>
        <span className="text-[10px] mt-1 text-center px-2">Image failed to load</span>
      </div>
    );
  }

  return (
    <img 
      src={src} 
      alt={alt} 
      referrerPolicy="no-referrer"
      onError={() => setError(true)}
      className="w-full h-full object-cover object-top"
      style={{
        mixBlendMode: "normal"
      }}
    />
  );
};

const StatCard = ({ label, value, Icon, onClick, isInteractive }: { label: string, value: string, Icon: any, onClick?: () => void, isInteractive?: boolean }) => (
  <div 
    onClick={onClick}
    className={`bg-white dark:bg-slate-800 p-4 rounded-xl shadow-sm border border-slate-200 dark:border-slate-600 flex items-center space-x-4 transition-all hover:shadow-md 
      ${isInteractive ? 'cursor-pointer ring-2 ring-transparent hover:ring-blue-200 dark:hover:ring-blue-900 hover:scale-[1.02] active:scale-95 group' : ''}
    `}
  >
    <div className={`p-3 rounded-lg transition-colors ${isInteractive ? 'bg-blue-50 dark:bg-blue-900/30 text-blue-600 dark:text-blue-400 group-hover:bg-blue-600 group-hover:text-white' : 'bg-blue-50 dark:bg-blue-900/30 text-blue-600 dark:text-blue-400'}`}>
      <Icon size={24} />
    </div>
    <div>
      <p className="text-slate-500 dark:text-slate-400 text-xs uppercase font-semibold tracking-wider flex items-center gap-1">
        {label}
        {isInteractive && <ExternalLink size={10} className="text-blue-400 print:hidden" />}
      </p>
      <p className="text-slate-900 dark:text-white font-bold text-lg">{value}</p>
    </div>
  </div>
);

const ExperienceCard = ({ job, isLast }: { job: typeof experience[0], isLast: boolean }) => {
  const [isOpen, setIsOpen] = useState(true);

  return (
    <div className="relative pl-8 pb-8 print:pb-4 break-inside-avoid">
      {!isLast && <div className="absolute left-[11px] top-8 bottom-0 w-0.5 bg-slate-200 dark:bg-slate-700 print:bg-slate-300"></div>}
      <div className="absolute left-0 top-1.5 w-6 h-6 rounded-full border-4 border-white dark:border-slate-800 bg-blue-600 shadow-md z-10 print:border-slate-200"></div>

      <div className="bg-white dark:bg-slate-800 rounded-xl shadow-sm border border-slate-100 dark:border-slate-700 overflow-hidden transition-all hover:shadow-md print:shadow-none print:border-none print:p-0">
        <div 
          className="p-5 cursor-pointer flex justify-between items-start print:p-0 print:cursor-default"
          onClick={() => setIsOpen(!isOpen)}
        >
          <div className="w-full">
            <div className="flex flex-col sm:flex-row sm:items-center justify-between gap-2 mb-1">
              <div className="flex flex-col sm:flex-row sm:items-center gap-2">
                <h3 className="text-lg font-bold text-slate-800 dark:text-slate-100">{job.role}</h3>
                <span className="hidden sm:inline text-slate-300 dark:text-slate-600 print:hidden">•</span>
                <span className="text-blue-600 dark:text-blue-400 font-semibold">{job.company}</span>
              </div>
              <div className="flex items-center gap-2">
                {job.type && <span className="text-xs bg-slate-100 dark:bg-slate-700 text-slate-600 dark:text-slate-300 px-2 py-0.5 rounded border border-slate-200 dark:border-slate-600 print:hidden">{job.type}</span>}
              </div>
            </div>
            <div className="flex flex-col sm:flex-row sm:justify-between sm:items-center w-full">
               <p className="text-slate-500 dark:text-slate-400 text-sm flex items-center gap-2">
                 <Calendar size={14} /> {job.period}
               </p>
               {job.note && (
                  <p className="text-xs text-amber-600 dark:text-amber-400 mt-2 sm:mt-0 font-medium bg-amber-50 dark:bg-amber-900/20 inline-block px-2 py-1 rounded border border-amber-100 dark:border-amber-800/50">
                    🚀 {job.note}
                  </p>
               )}
            </div>
          </div>
          <button className="text-slate-400 hover:text-blue-600 dark:hover:text-blue-400 transition-colors ml-4 print:hidden">
            {isOpen ? <ChevronUp size={20} /> : <ChevronDown size={20} />}
          </button>
        </div>

        {/* Always visible in print, conditionally in view */}
        <div className={`${isOpen ? 'block' : 'hidden'} print:block`}>
          <div className="px-5 pb-5 print:px-0 print:pb-2 border-t border-slate-50 dark:border-slate-700/50 print:border-none animate-in fade-in slide-in-from-top-2 duration-300">
            <p className="text-slate-600 dark:text-slate-300 mb-3 mt-3 italic text-sm border-l-2 border-blue-200 dark:border-blue-800 pl-3 print:border-l-4 print:border-blue-200">
              {job.description}
            </p>
            <ul className="space-y-2 print:space-y-1">
              {job.achievements.map((item, idx) => (
                <li key={idx} className="flex items-start text-sm text-slate-700 dark:text-slate-300 group">
                  <span className="mr-2 text-green-500 dark:text-green-400 mt-1 transition-transform group-hover:scale-125 print:text-black">✔</span>
                  {item}
                </li>
              ))}
            </ul>
          </div>
        </div>
      </div>
    </div>
  );
};

// --- Custom Chart Component ---
const CareerVelocityChart = () => {
  // Data representing career progression: Year vs "Impact Level" (Approximate Seniority)
  const data = [
    { year: 2015, level: 2, role: "Economist", company: "Moriah" },
    { year: 2016, level: 3, role: "Dept Manager", company: "Moriah" },
    { year: 2017, level: 4, role: "Analyst", company: "Ex Libris (Pivot)" }, 
    { year: 2018, level: 5, role: "Team Lead", company: "Ex Libris" },
    { year: 2019, level: 6, role: "Manager", company: "Ex Libris" },
    { year: 2021, level: 7, role: "Director", company: "Ex Libris" },
    { year: 2022, level: 8, role: "Snr Director", company: "Bizzabo" },
    { year: 2023, level: 9, role: "FP&A Director", company: "Fireblocks" }
  ];

  // Colors for each company
  const getCompanyColor = (companyName: string) => {
    if (companyName.includes("Moriah")) return "#f59e0b"; // Amber
    if (companyName.includes("Ex Libris")) return "#3b82f6"; // Blue
    if (companyName.includes("Bizzabo")) return "#8b5cf6"; // Purple
    if (companyName.includes("Fireblocks")) return "#10b981"; // Emerald
    return "#64748b"; // Slate default
  };

  // Increased internal resolution for sharper rendering
  const width = 800;
  const height = 450;
  const padding = 60; 

  const minYear = 2015;
  const maxYear = 2023; // Adjusted to match data end
  const minLevel = 0;
  const maxLevel = 10;

  // Generate array of all years for the axis
  const allYears = Array.from({ length: maxYear - minYear + 1 }, (_, i) => minYear + i);

  const getX = (year: number) => padding + ((year - minYear) / (maxYear - minYear)) * (width - 2 * padding);
  const getY = (level: number) => height - padding - ((level - minLevel) / (maxLevel - minLevel)) * (height - 2 * padding);

  // Generate points for the area fill
  const points = data.map(d => `${getX(d.year)},${getY(d.level)}`).join(" ");
  const areaPoints = `${getX(data[0].year)},${height-padding} ${points} ${getX(data[data.length-1].year)},${height-padding}`;

  const [hoveredPoint, setHoveredPoint] = useState<number | null>(null);

  return (
    <div className="w-full overflow-hidden rounded-xl bg-slate-50 dark:bg-slate-900 border border-slate-200 dark:border-slate-700 p-4 mb-6 shadow-inner">
      
      <div className="relative w-full h-80 sm:h-96">
        <svg viewBox={`0 0 ${width} ${height}`} className="w-full h-full overflow-visible">
          <defs>
            <linearGradient id="areaGradient" x1="0" y1="0" x2="0" y2="1">
              <stop offset="0%" stopColor="#64748b" stopOpacity="0.1" />
              <stop offset="100%" stopColor="#64748b" stopOpacity="0" />
            </linearGradient>
          </defs>

          {/* Grid Lines */}
          {[0, 2.5, 5, 7.5, 10].map(level => (
            <line 
              key={level}
              x1={padding} 
              y1={getY(level)} 
              x2={width - padding} 
              y2={getY(level)} 
              stroke="currentColor" 
              className="text-slate-200 dark:text-slate-700" 
              strokeWidth="1" 
              strokeDasharray="4 4"
            />
          ))}

          {/* Area Fill - Subtle background */}
          <path d={`M${areaPoints} Z`} fill="url(#areaGradient)" />

          {/* Multi-colored Line Segments */}
          {data.map((d, i) => {
            if (i === data.length - 1) return null;
            const next = data[i + 1];
            // Use the company color of the destination point for the segment leading to it, 
            // or the start point? Usually visualizing the 'era'. 
            // Let's use the start point's company to represent "Time spent at X".
            const segmentColor = getCompanyColor(d.company);
            
            return (
              <line
                key={`line-${i}`}
                x1={getX(d.year)}
                y1={getY(d.level)}
                x2={getX(next.year)}
                y2={getY(next.level)}
                stroke={segmentColor}
                strokeWidth="5"
                strokeLinecap="round"
                strokeLinejoin="round"
                className="drop-shadow-sm"
              />
            );
          })}

          {/* Data Points */}
          {data.map((d, i) => (
            <g 
              key={i} 
              onMouseEnter={() => setHoveredPoint(i)}
              onMouseLeave={() => setHoveredPoint(null)}
              className="cursor-pointer group"
            >
              {/* Invisible larger hit area */}
              <circle cx={getX(d.year)} cy={getY(d.level)} r="25" fill="transparent" />
              
              {/* Visible dot */}
              <circle 
                cx={getX(d.year)} 
                cy={getY(d.level)} 
                r={hoveredPoint === i ? 10 : 7} 
                className="fill-white dark:fill-slate-800 transition-all duration-300"
                stroke={getCompanyColor(d.company)}
                strokeWidth={4}
              />

              {/* Tooltip Label */}
              <foreignObject 
                x={getX(d.year) - 75} 
                y={getY(d.level) - 70} 
                width="150" 
                height="60" 
                className={`transition-opacity duration-200 pointer-events-none ${
                    (hoveredPoint === i || i === data.length - 1 || i === 0) ? 'opacity-100' : 'opacity-0'
                }`}
              >
                <div className="flex flex-col items-center justify-center text-center">
                    <span 
                        className="text-sm font-bold text-white px-3 py-1 rounded shadow-lg whitespace-nowrap z-10"
                        style={{ backgroundColor: getCompanyColor(d.company) }}
                    >
                        {d.role}
                    </span>
                    <span className="text-xs font-medium text-slate-600 bg-white/90 dark:bg-slate-900/90 px-2 py-0.5 rounded mt-1 border border-slate-200 dark:border-slate-700">
                        {d.year} • {d.company.split(' ')[0]}
                    </span>
                </div>
              </foreignObject>
            </g>
          ))}
          
          {/* Axis Labels - Show All Years */}
          {allYears.map(year => (
             <text 
                key={year}
                x={getX(year)} 
                y={height - 20} 
                className="text-sm font-medium fill-slate-400 dark:fill-slate-500" 
                textAnchor="middle"
             >
                {year}
             </text>
          ))}
        </svg>
      </div>
      
      {/* Legend */}
      <div className="flex flex-wrap justify-center gap-4 mt-6">
         {[
           { name: "Moriah", color: "#f59e0b" },
           { name: "Ex Libris", color: "#3b82f6" },
           { name: "Bizzabo", color: "#8b5cf6" },
           { name: "Fireblocks", color: "#10b981" }
         ].map((item) => (
            <div key={item.name} className="flex items-center gap-2">
                <div className="w-3 h-3 rounded-full" style={{ backgroundColor: item.color }}></div>
                <span className="text-xs text-slate-500 dark:text-slate-400 font-medium">{item.name}</span>
            </div>
         ))}
      </div>
    </div>
  );
};


// --- Modals ---

const Modal = ({ isOpen, onClose, title, children }: any) => {
  // Prevent body scroll when modal is open
  useEffect(() => {
    if (isOpen) {
      document.body.style.overflow = 'hidden';
    } else {
      document.body.style.overflow = 'unset';
    }
    return () => { document.body.style.overflow = 'unset'; }
  }, [isOpen]);

  if (!isOpen) return null;

  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center p-4 bg-slate-900/60 backdrop-blur-sm animate-in fade-in duration-200 print:hidden" onClick={onClose}>
      <div className="bg-white dark:bg-slate-800 rounded-2xl shadow-2xl w-full max-w-lg max-h-[90vh] overflow-y-auto relative animate-in zoom-in-95 duration-200 border dark:border-slate-700" onClick={e => e.stopPropagation()}>
        <div className="p-6 border-b border-slate-100 dark:border-slate-700 flex justify-between items-center sticky top-0 bg-white dark:bg-slate-800 z-10">
          <h2 className="text-xl font-bold text-slate-900 dark:text-white">{title}</h2>
          <button onClick={onClose} className="p-2 hover:bg-slate-100 dark:hover:bg-slate-700 rounded-full text-slate-400 hover:text-slate-700 dark:hover:text-slate-200 transition-colors">
            <X size={24} />
          </button>
        </div>
        <div className="p-6 dark:text-slate-300">
          {children}
        </div>
      </div>
    </div>
  );
};

const MinimalEmailPopup = ({ isOpen, onClose, onCopy, copied, email }: any) => {
  if (!isOpen) return null;
  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/10 backdrop-blur-[1px] animate-in fade-in duration-200" onClick={onClose}>
        <div className="bg-white dark:bg-slate-800 rounded-xl shadow-2xl p-4 transform scale-100 animate-in zoom-in-95 duration-100 border border-slate-100 dark:border-slate-700 flex flex-col gap-3 w-64" onClick={e => e.stopPropagation()}>
             <p className="text-xs font-bold text-slate-400 uppercase tracking-wider text-center mb-1">Contact Options</p>
             <button 
                onClick={onCopy}
                className="flex items-center gap-3 w-full p-2 hover:bg-slate-100 dark:hover:bg-slate-700/50 rounded-lg transition-colors text-left group"
             >
                <div className={`p-2 rounded-md ${copied ? 'bg-green-100 text-green-600' : 'bg-slate-100 dark:bg-slate-700 text-slate-600 dark:text-slate-300 group-hover:bg-white dark:group-hover:bg-slate-600'}`}>
                    {copied ? <Check size={16} /> : <Copy size={16} />}
                </div>
                <span className="text-sm font-medium text-slate-700 dark:text-slate-200">{copied ? 'Copied!' : 'Copy Address'}</span>
             </button>
             
             <a 
                href={`mailto:${email}`}
                className="flex items-center gap-3 w-full p-2 hover:bg-slate-100 dark:hover:bg-slate-700/50 rounded-lg transition-colors text-left group"
             >
                <div className="p-2 rounded-md bg-slate-100 dark:bg-slate-700 text-slate-600 dark:text-slate-300 group-hover:bg-white dark:group-hover:bg-slate-600">
                    <ExternalLink size={16} />
                </div>
                <span className="text-sm font-medium text-slate-700 dark:text-slate-200">Open Mail App</span>
             </a>
        </div>
    </div>
  );
};

const MinimalPhonePopup = ({ isOpen, onClose, onCopy, copied, phone }: any) => {
  if (!isOpen) return null;
  return (
    <div className="fixed inset-0 z-50 flex items-center justify-center bg-black/10 backdrop-blur-[1px] animate-in fade-in duration-200" onClick={onClose}>
        <div className="bg-white dark:bg-slate-800 rounded-xl shadow-2xl p-4 transform scale-100 animate-in zoom-in-95 duration-100 border border-slate-100 dark:border-slate-700 flex flex-col gap-3 w-64" onClick={e => e.stopPropagation()}>
             <p className="text-xs font-bold text-slate-400 uppercase tracking-wider text-center mb-1">Contact Options</p>
             <button 
                onClick={onCopy}
                className="flex items-center gap-3 w-full p-2 hover:bg-slate-100 dark:hover:bg-slate-700/50 rounded-lg transition-colors text-left group"
             >
                <div className={`p-2 rounded-md ${copied ? 'bg-green-100 text-green-600' : 'bg-slate-100 dark:bg-slate-700 text-slate-600 dark:text-slate-300 group-hover:bg-white dark:group-hover:bg-slate-600'}`}>
                    {copied ? <Check size={16} /> : <Copy size={16} />}
                </div>
                <span className="text-sm font-medium text-slate-700 dark:text-slate-200">{copied ? 'Copied!' : 'Copy Number'}</span>
             </button>
             
             <a 
                href={`tel:${phone}`}
                className="flex items-center gap-3 w-full p-2 hover:bg-slate-100 dark:hover:bg-slate-700/50 rounded-lg transition-colors text-left group"
             >
                <div className="p-2 rounded-md bg-slate-100 dark:bg-slate-700 text-slate-600 dark:text-slate-300 group-hover:bg-white dark:group-hover:bg-slate-600">
                    <Phone size={16} />
                </div>
                <span className="text-sm font-medium text-slate-700 dark:text-slate-200">Call Number</span>
             </a>
        </div>
    </div>
  );
};

export default function App() {
  const [activeModal, setActiveModal] = useState<null | 'systems' | 'experience' | 'education' | 'email' | 'phone'>(null);
  const [isDarkMode, setIsDarkMode] = useState(false);
  const [copied, setCopied] = useState(false);

  const handleStatClick = (type?: string) => {
    if (type === 'systems') setActiveModal('systems');
    if (type === 'experience') setActiveModal('experience');
  };

  const handlePrint = () => {
    window.print();
  };

  const toggleTheme = () => {
    setIsDarkMode(!isDarkMode);
  };

  const handleCopyEmail = () => {
    // Robust clipboard copy for iframe environments
    const textArea = document.createElement("textarea");
    textArea.value = profile.contact.email;
    document.body.appendChild(textArea);
    textArea.select();
    try {
      document.execCommand("copy");
      setCopied(true);
      setTimeout(() => {
        setCopied(false);
        setActiveModal(null);
      }, 1500);
    } catch (err) {
      console.error('Failed to copy', err);
    }
    document.body.removeChild(textArea);
  };

  const handleCopyPhone = () => {
    // Robust clipboard copy for iframe environments
    const textArea = document.createElement("textarea");
    textArea.value = profile.contact.phone;
    document.body.appendChild(textArea);
    textArea.select();
    try {
      document.execCommand("copy");
      setCopied(true);
      setTimeout(() => {
        setCopied(false);
        setActiveModal(null);
      }, 1500);
    } catch (err) {
      console.error('Failed to copy', err);
    }
    document.body.removeChild(textArea);
  };

  return (
    <div className={`${isDarkMode ? 'dark' : ''}`}>
      <div className="min-h-screen bg-slate-50 dark:bg-slate-900 text-slate-800 dark:text-slate-200 font-sans selection:bg-blue-100 selection:text-blue-900 pb-12 transition-colors duration-300 print:bg-white print:text-black">
        
        {/* Floating Actions */}
        <div className="fixed bottom-6 right-6 flex flex-col gap-3 z-40 print:hidden">
          <button 
            onClick={toggleTheme}
            className="p-3 rounded-full bg-white dark:bg-slate-800 text-slate-700 dark:text-slate-200 shadow-lg border border-slate-200 dark:border-slate-700 hover:scale-110 transition-transform"
            title="Toggle Theme"
          >
            {isDarkMode ? <Sun size={20} /> : <Moon size={20} />}
          </button>
          <button 
            onClick={handlePrint}
            className="p-3 rounded-full bg-blue-600 text-white shadow-lg shadow-blue-600/30 hover:bg-blue-700 hover:scale-110 transition-transform"
            title="Save as PDF"
          >
            <Download size={20} />
          </button>
        </div>

        {/* Systems Modal */}
        <Modal isOpen={activeModal === 'systems'} onClose={() => setActiveModal(null)} title="Technical Ecosystem">
           <div className="space-y-6">
            {skillsDetail.map((category, idx) => (
              <div key={idx}>
                <h3 className="text-sm font-bold text-slate-400 uppercase tracking-wider mb-3 border-l-4 border-blue-500 pl-3">
                  {category.category}
                </h3>
                <div className="grid grid-cols-3 gap-4">
                  {category.items.map((tool, tIdx) => (
                    <div key={tIdx} className="flex flex-col items-center justify-center p-3 rounded-xl bg-slate-50 dark:bg-slate-700/50 border border-slate-100 dark:border-slate-600 hover:border-blue-200 hover:bg-white dark:hover:bg-slate-700 hover:shadow-lg transition-all group cursor-pointer">
                      <div className="w-12 h-12 bg-white rounded-full flex items-center justify-center mb-2 shadow-sm p-2 group-hover:scale-110 transition-transform overflow-hidden">
                        <img 
                          src={`https://www.google.com/s2/favicons?domain=${tool.domain}&sz=64`} 
                          alt={tool.name} 
                          className="w-8 h-8 object-contain"
                          onError={(e) => {
                            (e.target as HTMLImageElement).style.display = 'none';
                          }}
                        />
                      </div>
                      <span className="font-semibold text-slate-700 dark:text-slate-200 text-xs text-center">{tool.name}</span>
                    </div>
                  ))}
                </div>
              </div>
            ))}
          </div>
          <p className="mt-6 text-xs text-slate-400 text-center">Experienced in full implementation & administration of all listed stacks.</p>
        </Modal>

        {/* Minimalist Email Popup */}
        <MinimalEmailPopup 
            isOpen={activeModal === 'email'} 
            onClose={() => setActiveModal(null)} 
            onCopy={handleCopyEmail}
            copied={copied}
            email={profile.contact.email}
        />

        {/* Minimalist Phone Popup */}
        <MinimalPhonePopup 
            isOpen={activeModal === 'phone'} 
            onClose={() => setActiveModal(null)} 
            onCopy={handleCopyPhone}
            copied={copied}
            phone={profile.contact.phone}
        />

        {/* Experience Summary Modal */}
        <Modal isOpen={activeModal === 'experience'} onClose={() => setActiveModal(null)} title="Career Progression">
          {/* New Interactive Chart Added Here */}
          <CareerVelocityChart />
          
          <div className="relative border-l-2 border-blue-200 dark:border-blue-800 ml-3 my-4 space-y-8">
             <div className="relative pl-6">
                <div className="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-blue-600 border-2 border-white dark:border-slate-800"></div>
                <h4 className="font-bold text-slate-900 dark:text-white">Director Level (2022-Present)</h4>
                <p className="text-sm text-slate-600 dark:text-slate-400">Leading FP&A for global SaaS companies (Fireblocks, Bizzabo). Strategic partner to C-Suite.</p>
             </div>
             <div className="relative pl-6">
                <div className="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-blue-400 border-2 border-white dark:border-slate-800"></div>
                <h4 className="font-bold text-slate-900 dark:text-white">Managerial Growth (2017-2022)</h4>
                <p className="text-sm text-slate-600 dark:text-slate-400">Rapid promotion at Ex Libris from Analyst to Team Leader to Director.</p>
             </div>
             <div className="relative pl-6">
                <div className="absolute -left-[9px] top-0 w-4 h-4 rounded-full bg-blue-200 border-2 border-white dark:border-slate-800"></div>
                <h4 className="font-bold text-slate-900 dark:text-white">Foundation (2015-2017)</h4>
                <p className="text-sm text-slate-600 dark:text-slate-400">Managing 6.5B NIS budgets at Moriah. Built core economic skills.</p>
             </div>
          </div>
        </Modal>

        {/* Education Modal */}
        <Modal isOpen={activeModal === 'education'} onClose={() => setActiveModal(null)} title="Academic Background">
           <div className="flex flex-col items-center text-center space-y-6">
              <div className="p-4 bg-white rounded-xl shadow-sm">
                <img 
                  src="https://upload.wikimedia.org/wikipedia/en/thumb/9/98/Hebrew_University_of_Jerusalem_Logo.svg/1200px-Hebrew_University_of_Jerusalem_Logo.svg.png" 
                  alt="HUJI Logo" 
                  className="h-24 object-contain opacity-90" 
                />
              </div>
              {education.map((edu, idx) => (
                <a 
                  key={idx} 
                  href={edu.link}
                  target="_blank"
                  rel="noreferrer"
                  className="w-full bg-slate-50 dark:bg-slate-700/50 p-4 rounded-xl border border-slate-200 dark:border-slate-600 hover:border-blue-400 hover:shadow-md transition-all group text-left block"
                >
                  <div className="flex justify-between items-start">
                    <div>
                      <h4 className="font-bold text-slate-900 dark:text-white group-hover:text-blue-700 dark:group-hover:text-blue-400 transition-colors flex items-center gap-2">
                        {edu.degree}
                        <ExternalLink size={14} className="opacity-0 group-hover:opacity-100 transition-opacity" />
                      </h4>
                      <p className="text-sm text-slate-600 dark:text-slate-300">{edu.school}</p>
                      <p className="text-xs text-slate-400">{edu.year}</p>
                    </div>
                  </div>
                </a>
              ))}
           </div>
        </Modal>

        {/* --- Header --- */}
        <header className="bg-slate-900 dark:bg-slate-950 text-white pt-10 pb-20 px-4 sm:px-8 relative overflow-hidden print:bg-white print:text-black print:pb-0 print:pt-0 print:border-b-2 print:border-slate-200">
          {/* Background Effects (Hidden on Print) */}
          
          <div className="max-w-5xl mx-auto relative z-10 flex flex-col md:flex-row items-center md:items-start gap-8 print:flex-row print:items-start print:gap-6">
            
            {/* Profile Picture with Tech Effect */}
            <div className="relative shrink-0 print:hidden">
              <div className="w-32 h-32 md:w-40 md:h-40 rounded-full border-4 border-blue-500/50 shadow-[0_0_30px_rgba(59,130,246,0.5)] overflow-hidden relative group">
                 {/* Replaced fixed image with safer Avatar component */}
                 <Avatar src="https://www.dropbox.com/scl/fi/8ux045w3zhyjcia7wb518/666.png?rlkey=5i3kh2w5li4ot4wt2ycgc5gc2&st=iudygyo3&raw=1" alt={profile.name} initials={profile.initials} />
                 {/* Removed the overlay div that was affecting clarity */}
              </div>
              {/* Tech Decoration Dots */}
              <div className="absolute -right-2 top-1/2 w-2 h-2 bg-cyan-400 rounded-full animate-pulse"></div>
              <div className="absolute -left-1 top-1/4 w-1 h-1 bg-blue-400 rounded-full"></div>
            </div>

            <div className="flex-grow text-center md:text-left print:text-left">
              <h1 className="text-4xl md:text-5xl font-extrabold tracking-tight mb-2 print:text-slate-900 print:mb-1">
                {profile.name}
              </h1>
              <h2 className="text-xl md:text-2xl text-blue-400 font-light flex items-center justify-center md:justify-start gap-2 print:text-slate-600 print:text-xl print:font-bold">
                <TrendingUp size={24} className="print:hidden" />
                {profile.role}
              </h2>
              
              {/* Screen Contact Info */}
              <div className="mt-6 flex flex-wrap justify-center md:justify-start gap-3 text-sm text-slate-300 print:hidden">
                <button 
                  onClick={() => setActiveModal('email')}
                  className="flex items-center gap-2 bg-white/10 hover:bg-white/20 px-4 py-2 rounded-full transition-colors cursor-pointer"
                >
                  <Mail size={16} className="text-blue-400" /> {profile.contact.email}
                </button>
                <a 
                  href={profile.contact.linkedin}
                  target="_blank"
                  rel="noopener noreferrer"
                  className="flex items-center gap-2 bg-white/10 px-4 py-2 rounded-full hover:bg-white/20 transition-colors"
                >
                  <Linkedin size={16} className="text-blue-400" /> LinkedIn
                </a>
                <button 
                    onClick={() => setActiveModal('phone')}
                    className="flex items-center gap-2 bg-white/10 hover:bg-white/20 px-4 py-2 rounded-full transition-colors cursor-pointer"
                >
                  <Phone size={16} className="text-blue-400" /> {profile.contact.phone}
                </button>
                <a 
                  href="https://wa.me/972533363652" 
                  target="_blank" 
                  rel="noopener noreferrer"
                  className="flex items-center justify-center w-10 h-10 bg-white/10 rounded-full hover:bg-white/20 transition-all group"
                  title="Chat on WhatsApp"
                >
                  <img 
                    src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" 
                    alt="WhatsApp" 
                    className="w-6 h-6 object-contain" 
                  />
                </a>
              </div>

              {/* Print Only Contact Info */}
              <div className="hidden print:flex flex-wrap gap-4 mt-4 text-sm text-slate-600">
                 <span className="flex items-center gap-1"><Mail size={14}/> {profile.contact.email}</span>
                 <span className="flex items-center gap-1"><Phone size={14}/> {profile.contact.phone}</span>
                 <span className="flex items-center gap-1"><Linkedin size={14}/> {profile.contact.linkedin}</span>
              </div>

            </div>
          </div>
        </header>

        {/* --- Main Content --- */}
        <main className="max-w-5xl mx-auto px-4 sm:px-8 -mt-12 relative z-20 print:mt-6 print:px-0">
          
          {/* --- Key Stats Grid (Hidden on Print if purely interactive, but kept here for info) --- */}
          <div className="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 mb-8 print:grid-cols-4 print:gap-2">
            {profile.highlights.map((stat, idx) => (
              <StatCard 
                key={idx} 
                label={stat.label} 
                value={stat.value} 
                Icon={stat.icon} 
                isInteractive={stat.isInteractive}
                onClick={() => handleStatClick(stat.type)}
              />
            ))}
          </div>

          <div className="grid grid-cols-1 lg:grid-cols-3 gap-8 print:block">
            
            {/* --- Left Column --- */}
            <div className="lg:col-span-2 space-y-8 print:space-y-6">
              <section className="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-sm border border-slate-100 dark:border-slate-700 hover:shadow-md transition-shadow print:shadow-none print:border-none print:p-0">
                <h3 className="text-lg font-bold text-slate-900 dark:text-white mb-3 flex items-center gap-2 print:text-xl print:border-b print:border-slate-300 print:pb-1">
                  <span className="w-1 h-6 bg-blue-600 rounded-full print:hidden"></span>
                  Executive Summary
                </h3>
                <p className="text-slate-600 dark:text-slate-300 leading-relaxed print:text-justify print:text-sm">
                  {profile.summary}
                </p>
              </section>

              <section>
                <h3 className="text-xl font-bold text-slate-900 dark:text-white mb-6 flex items-center gap-2 print:text-xl print:mb-4 print:border-b print:border-slate-300 print:pb-1">
                  <Layers size={24} className="text-blue-600 dark:text-blue-400 print:hidden" />
                  Professional Experience
                </h3>
                <div className="pl-2 print:pl-0">
                  {experience.map((job, idx) => (
                    <ExperienceCard 
                      key={job.id} 
                      job={job} 
                      isLast={idx === experience.length - 1} 
                    />
                  ))}
                </div>
              </section>
            </div>

            {/* --- Right Column --- */}
            <div className="space-y-8 print:hidden"> {/* Hide interactive right column in print, standard CVs often linearize or we save space */}
              <section className="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-sm border border-slate-100 dark:border-slate-700 hover:shadow-md transition-shadow">
                <div className="flex justify-between items-center border-b dark:border-slate-700 pb-2 mb-4">
                  <h3 className="text-lg font-bold text-slate-900 dark:text-white flex items-center gap-2">
                    <Database size={20} className="text-blue-600 dark:text-blue-400" />
                    Tech Stack
                  </h3>
                  <button 
                    onClick={() => setActiveModal('systems')}
                    className="text-xs text-blue-600 dark:text-blue-400 hover:text-blue-800 font-medium hover:underline"
                  >
                    View All Logos
                  </button>
                </div>
                <div className="flex flex-wrap gap-2">
                  {['NetSuite', 'Salesforce', 'Planful', 'Excel', 'Power BI', 'Mesh', 'Tipalti'].map((tool, i) => (
                     <span key={i} className="px-2 py-1 bg-slate-100 dark:bg-slate-700 text-slate-600 dark:text-slate-300 text-xs rounded border border-slate-200 dark:border-slate-600">
                       {tool}
                     </span>
                  ))}
                  <span className="text-xs text-slate-400 py-1 cursor-pointer hover:text-blue-500" onClick={() => setActiveModal('systems')}>+7 more</span>
                </div>
              </section>

              {/* Education Section - Interactive */}
              <section 
                className="bg-white dark:bg-slate-800 p-6 rounded-2xl shadow-sm border border-slate-100 dark:border-slate-700 hover:shadow-md transition-all cursor-pointer group relative overflow-hidden"
                onClick={() => setActiveModal('education')}
              >
                <div className="absolute top-0 right-0 p-3 opacity-0 group-hover:opacity-100 transition-opacity">
                   <ExternalLink className="text-blue-500" size={16} />
                </div>
                <h3 className="text-lg font-bold text-slate-900 dark:text-white mb-4 flex items-center gap-2 border-b dark:border-slate-700 pb-2">
                  <GraduationCap size={20} className="text-blue-600 dark:text-blue-400" />
                  Education
                </h3>
                <div className="space-y-4">
                  {education.map((edu, idx) => (
                    <div key={idx} className="relative pl-4 border-l-2 border-slate-100 dark:border-slate-700 group-hover:border-blue-200 transition-colors">
                      <h4 className="font-bold text-slate-800 dark:text-slate-100">{edu.degree}</h4>
                      <p className="text-sm text-slate-600 dark:text-slate-400">{edu.school}</p>
                      <p className="text-xs text-slate-400 mt-1">{edu.year}</p>
                    </div>
                  ))}
                </div>
                <div className="mt-4 text-center text-xs text-blue-600 dark:text-blue-400 font-medium opacity-0 group-hover:opacity-100 transition-opacity">
                  Click to view credentials & university site
                </div>
              </section>

              <section className="bg-gradient-to-br from-amber-50 to-orange-50 dark:from-amber-900/20 dark:to-orange-900/10 p-6 rounded-2xl border border-amber-100 dark:border-amber-900/30 shadow-sm hover:shadow-md transition-shadow">
                <h3 className="text-lg font-bold text-amber-800 dark:text-amber-500 mb-2 flex items-center gap-2">
                  <Award size={20} />
                  Honors
                </h3>
                <div className="bg-white/60 dark:bg-slate-800/50 p-3 rounded-lg backdrop-blur-sm">
                  <p className="font-bold text-slate-800 dark:text-slate-100">Outstanding Employee Award</p>
                  <p className="text-sm text-slate-600 dark:text-slate-400">G&A Business Unit, 2019</p>
                </div>
              </section>
            </div>
            
            {/* --- Print Only Right Column content (re-rendered linearly for print) --- */}
             <div className="hidden print:block mt-6">
                <h3 className="text-xl font-bold text-slate-900 mb-4 border-b border-slate-300 pb-1">Education & Skills</h3>
                <div className="grid grid-cols-2 gap-6">
                    <div>
                         <h4 className="font-bold mb-2">Education</h4>
                         {education.map((edu, idx) => (
                            <div key={idx} className="mb-3">
                                <div className="font-bold text-sm">{edu.degree}</div>
                                <div className="text-sm">{edu.school}, {edu.year}</div>
                            </div>
                         ))}
                    </div>
                    <div>
                        <h4 className="font-bold mb-2">Key Technologies</h4>
                        <div className="text-sm">
                            NetSuite, Salesforce, Planful, Excel, Power BI, Mesh, Tipalti, VBA, SQL
                        </div>
                    </div>
                </div>
             </div>

          </div>
        </main>

        <footer className="max-w-5xl mx-auto mt-12 text-center text-slate-400 text-sm print:hidden">
          <p>© {new Date().getFullYear()} Aviad Dahan-Weiss • Interactive CV</p>
        </footer>
      </div>
    </div>
  );
}
