# Internal Structure

::left::

<div className="flex flex-col items-center space-y-4">
  <div className="flex flex-col items-center box1 p-4 space-y-4 w-full">
    <div className="text-center w-full"><pre>react-dom</pre></div>
    <div className="box2 p-4 text-center w-full">React Reconciler</div>
    <div className="box3 p-4 text-center w-full h-25">DOM API</div>
  </div>
  <div className="box1 p-4 text-center w-full h-40">React Core</div>
</div>

::right::

<div className="flex flex-col items-center space-y-4">
  <div className="flex flex-col items-center box1 p-4 space-y-4 w-full">
    <div className="text-center w-full"><pre>react-native</pre></div>
    <div className="box2 p-4 text-center w-full">React Reconciler</div>
    <div className="flex justify-around space-x-4 w-full">
      <div className="box3 p-4 text-center h-25">iOS View APIs</div>
      <div className="box3 p-4 text-center h-25">Android View APIs</div>
    </div>
  </div>
  <div className="box1 p-4 text-center w-full h-40">React Core</div>
</div>
