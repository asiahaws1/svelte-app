<script>
    export let variant = 'primary'; 
    export let label = 'Button';

</script>

<button
    class={`w-full max-w-xs m-8 h-12 rounded-full text-base flex items-center justify-center 
        ${variant === 'primary' ? 'bg-purple-600 text-white hover:bg-purple-700' : 
          variant === 'secondary' ? 'bg-gray-300 text-gray-800 hover:bg-gray-400' : 
          'bg-gray-200 text-red-800'}
        focus:outline-none`} 

>
    {label}
</button>
