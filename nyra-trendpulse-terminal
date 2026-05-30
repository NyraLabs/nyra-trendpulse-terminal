import SwiftUI

struct TrendPulseTerminalView: View {
    @State private var marketTrend: String = "صعودي 🚀"
    @State private var sentimentScore: Double = 88.5
    
    let goldColor = Color(red: 0.85, green: 0.65, blue: 0.2)
    
    var body: some View {
        ZStack {
            Color.black.ignoresSafeArea()
            
            VStack(spacing: 20) {
                Text("NYRA TRENDPULSE")
                    .font(.system(size: 24, weight: .bold, design: .monospaced))
                    .foregroundColor(goldColor)
                
                HStack {
                    VStack {
                        Text("السوق").foregroundColor(.gray)
                        Text(marketTrend).font(.title2).foregroundColor(.green)
                    }
                    Spacer()
                    VStack {
                        Text("مؤشر الذكاء").foregroundColor(.gray)
                        Text("\(sentimentScore, specifier: "%.1f")%").font(.title2).foregroundColor(goldColor)
                    }
                }
                .padding()
                .background(Color.white.opacity(0.05))
                .cornerRadius(12)
                
                Spacer()
                Text("نظام تتبع ذكي يحلل توجهات سولانا فورياً")
                    .foregroundColor(.gray)
                    .italic()
            }
            .padding()
        }
    }
}
