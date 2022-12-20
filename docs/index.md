<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html;charset=utf-8" >
    <title>ADCL: Acceleration Driven Clause Learning for Constrained Horn Clauses</title>
    <style>
      table, th, td {border: 1px solid black;}
      td {text-align: center}
    </style>
  </head>
  <body>

    <p>
      This is the empirical evaluation of the paper <a href="https://arxiv.org/abs/???"><i>ADCL: Acceleration Driven Clause Learning for Constrained Horn Clauses</i></a>.
      You can find the source code for our tool LoAT at <a href="https://github.com/loat-developers/LoAT/tree/adcl">GitHub</a>.
    </p>

    <p>Moreover, we refer to the <a href="https://loat-developers.github.io/LoAT/">general LoAT website</a> for further information.</p>

    <h1>Getting LoAT</h1>

    We provide a <a href="https://github.com/loat-developers/LoAT/releases/tag/adcl">pre-compiled binary of LoAT (Linux, 64 bit)</a>.

    <h1>Evaluation</h1>

    <h2>Examples</h2>
    
    <a href="./lia.zip">Here</a> you can find a zip file containing the examples that we used for our evaluation.

    It contains the 427 examples from <a href="https://github.com/chc-comp/chc-comp22-benchmarks/tree/497725c7c994cc06f74a8933ec292fa03a66ad48/LIA-Lin">the category LIA-Lin of the benchmark collection from the CHC-Comp '22</a> that do not use the operators <tt>div</tt> or <tt>mod</tt>.

    <h2>Results</h2>

    Below we provide tables with the detailed results of our benchmarks:
    <ul>
      <li><a href="./loat.html">LoAT</a></li>
      <ul>
        <li>invocation: <tt>loat-static --mode reachability --format horn $INPUT</tt></li>
      </ul>
      <li><a href="./z3.html">Z3</a></li>
      <ul>
        <li>invocation: <tt>z3 $INPUT</tt></li>
      </ul>
      <li><a href="./eld.html">Eldarica</a></li>
      <ul>
        <li>invocation: <tt>eld $INPUT</tt></li>
      </ul>
      <li><a href="./eld_stac.html">Eldarica with acceleration as pre-processing</a></li>
      <ul>
        <li>invocation: <tt>eld -stac $INPUT</tt></li>
      </ul>
    </ul>

  </body>
</html>
