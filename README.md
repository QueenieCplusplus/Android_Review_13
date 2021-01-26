# Android_Review_13
RecyclerView 循環目錄清單

1. see codeScript as below. It is corresponding with UI https://github.com/QueenieCplusplus/Android_Review_9 

      // go to app/src/main/java...../katesvideoapp/ui/Fragment.kt
      
      package com.example.android.katesvideoapp/ui
      
      [default module]
      
      [dataBind module]
      import com.example.android.katesvideoapp.R
      import com.example.android.katesvideoapp.databinding.KatesVideoAppItemBinding
      import com.example.android.katesvideoapp.databinding.FragmentKatesVideoAppBinding
      
      [intent module]
      import android.content.Intent
      
      [view Group module]
      import android.view.View
      import android.view.ViewGroup
      
      [inflater module]
      import android.view.LayoutInflater
      import androidx.fragment.app.Fragment
      
      [annotation module]
      import androidx.annotation.LayoutRes
      
      [Uri module]
      import android.net.Uri
      
      [observer module]
      import androidx.lifecycle.Observer
      
      [viewModel module]
      import androidx.lifecycle.viewModelProvider
      
      [recyclerView module]
      import androidx.recyclerview.widget.RecyclerView
      import androidx.recyclerview.widge.LinearLayout
      
      [data modules]
      import com.example.andorid.katesvideoapp.viewmodels.ViewModel
      import com.example.android.katesvideoapp.domain.Video
      
      class KatesVideoAppFragment: Fragment(){
      
      
      
              // TODO:
              // declair and define val ViewModel 此客製化類別的實例 
              // declair and define val by lazy in its body 利用懶加載初始化內部唯讀資料
              
              // TODO:
              // declair and define 適配器變數可空
              
              
              // 碎片的生命週期
              override fun onViewCreated(v: View, savedInstanceState: Bundle?){
              
                  super.onViewCreated(v, savedInstanceState)
                  
              
              }
              
            
      
      
      
      
      }

2. today's tip (lazy 懶加載)
