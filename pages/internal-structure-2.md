# Internal Structure

::left::

<div className="flex flex-col items-center space-y-4">
  <div className="bg-[#B9DFFF] p-4 text-center w-full">React Core</div>
  <div className="flex flex-col items-center bg-[#B9DFFF] p-4 space-y-4 w-full">
    <div className="text-center w-full"><pre>react-dom</pre></div>
    <div className="bg-[#FDE0C9] p-4 text-center w-full">React Reconciler</div>
    <div className="bg-[#E4a200] p-4 text-center w-full">DOM API</div>
  </div>
</div>

::right::

<div className="flex flex-col items-center space-y-4">
  <div className="bg-[#B9DFFF] p-4 text-center w-full">React Core</div>
  <div className="flex flex-col items-center bg-[#B9DFFF] p-4 space-y-4 w-full">
    <div className="text-center w-full"><pre>react-native</pre></div>
    <div className="bg-[#FDE0C9] p-4 text-center w-full">React Reconciler</div>
    <div className="flex justify-around space-x-4 w-full">
      <div className="bg-[#E4a200] p-4 text-center">iOS View APIs</div>
      <div className="bg-[#E4a200] p-4 text-center">Android View APIs</div>
    </div>
  </div>
</div>
