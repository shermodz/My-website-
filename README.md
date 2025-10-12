
Action: file_editor str_replace /app/frontend/src/pages/Home.jsx --old-str "      {/* Hero Section */}
      <section id=\"home\" className=\"pt-32 pb-20 px-6\">
        <div className=\"container mx-auto max-w-6xl\">
          <div className=\"text-center space-y-8\">
            <div className=\"float\">
              <Rocket size={80} className=\"mx-auto text-blue-400\" />
            </div>
            <h1 className=\"text-5xl md:text-7xl font-bold leading-tight\">
              Science is not a subject,
              <br />
              <span className=\"gradient-text\">it's a way to see the world</span>
            </h1>
            <p className=\"text-xl text-gray-300 max-w-3xl mx-auto leading-relaxed\">
              Welcome to Shermodz - where cutting-edge scientific knowledge meets innovative learning. 
              Explore, experiment, and expand your understanding of the universe.
            </p>
            <div className=\"flex flex-col sm:flex-row gap-4 justify-center mt-12\">
              <Button 
                size=\"lg\" 
                className=\"bg-blue-600 hover:bg-blue-700 text-white px-8 py-6 text-lg glow-blue\"
                onClick={() => scrollToSection('subjects')}
              >
                Start Learning <ArrowRight className=\"ml-2\" />
              </Button>
              <Button 
                size=\"lg\" 
                variant=\"outline\" 
                className=\"border-violet-500 text-violet-400 hover:bg-violet-500/20 px-8 py-6 text-lg\"
                onClick={() => scrollToSection('experiments')}
              >
                Try Experiments
              </Button>
            </div>
          </div>
        </div>
      </section>" --new-str "      {/* Hero Section */}
      <section id=\"home\" className=\"pt-32 pb-20 px-6\">
        <div className=\"container mx-auto max-w-6xl\">
          <div className=\"text-center space-y-8\">
            {/* Logo and Name */}
            <div className=\"flex flex-col items-center space-y-4 mb-8\">
              <img 
                src=\"https://customer-assets.emergentagent.com/job_sci-innovate/artifacts/sskpikir_copilot_image_1760107571547.jpeg\" 
                alt=\"Shermodz Logo\" 
                className=\"w-32 h-32 md:w-40 md:h-40 rounded-full object-cover glow-blue float\"
              />
              <h1 className=\"text-6xl md:text-8xl font-bold gradient-text\">SHERMODZ</h1>
              <p className=\"text-2xl md:text-3xl text-blue-300 font-semibold\">Scientific Resources</p>
            </div>

            {/* Main Quote */}
            <div className=\"max-w-4xl mx-auto space-y-6\">
              <h2 className=\"text-4xl md:text-5xl font-bold leading-tight text-white\">
                \"Science is not a subject,
                <br />
                <span className=\"gradient-text\">it's a way to see and invent the world\"</span>
              </h2>
              
              {/* Einstein Quote */}
              <div className=\"glass p-6 rounded-xl border border-violet-500/30\">
                <p className=\"text-xl md:text-2xl text-gray-100 italic leading-relaxed\">
                  \"Imagination is more important than knowledge, knowledge is limited but imagination encircles the world 🌎\"
                </p>
                <p className=\"text-sm text-gray-400 mt-3\">- Albert Einstein</p>
              </div>

              {/* Mission Statement */}
              <p className=\"text-2xl md:text-3xl text-white font-semibold leading-relaxed\">
                Shermodz will guide you to use science as an 
                <span className=\"text-blue-400\"> eye to see the world</span> and a 
                <span className=\"text-violet-400\"> hand to build the world</span>
              </p>
            </div>

            <p className=\"text-xl text-gray-300 max-w-3xl mx-auto leading-relaxed mt-8\">
              Where cutting-edge scientific knowledge meets innovative learning. 
              Explore, experiment, and expand your understanding of the universe.
            </p>
            
            <div className=\"flex flex-col sm:flex-row gap-4 justify-center mt-12\">
              <Button 
                size=\"lg\" 
                className=\"bg-blue-600 hover:bg-blue-700 text-white px-8 py-6 text-lg glow-blue\"
                onClick={() => scrollToSection('subjects')}
              >
                Start Learning <ArrowRight className=\"ml-2\" />
              </Button>
              <Button 
                size=\"lg\" 
                variant=\"outline\" 
                className=\"border-violet-500 text-violet-400 hover:bg-violet-500/20 px-8 py-6 text-lg\"
                onClick={() => scrollToSection('experiments')}
              >
                Try Experiments
              </Button>
            </div>
          </div>
        </div>
      </section>"
Observation: Edit was successful.
