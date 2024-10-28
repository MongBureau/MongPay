import React, { useState } from 'react';
import { Card, CardContent } from '@/components/ui/card';
import { Button } from '@/components/ui/button';
import { Send, History, Home, User, CreditCard } from 'lucide-react';

const Dashboard = () => {
    const [showPayAnimation, setShowPayAnimation] = useState(false);
    const [audio] = useState(new Audio('YOUR_SOUND_URL_HERE')); // Replace with your sound URL
  
    const handleTapToPay = () => {
      setShowPayAnimation(true);
      // Play the sound
      audio.currentTime = 0;
      audio.play().catch(e => console.log('Audio play failed:', e));
      
      // Auto-hide the animation after 5 seconds
      setTimeout(() => {
        setShowPayAnimation(false);
      }, 5000);
    };
  
    // Cleanup audio on component unmount
    useEffect(() => {
      return () => {
        audio.pause();
        audio.src = '';
      };
    }, [audio]);
  
  return (
    <div className="min-h-screen bg-gray-100 relative">
      {/* Tap to Pay Animation Overlay */}
      {showPayAnimation && (
        <div className="fixed inset-0 bg-black bg-opacity-90 z-50 flex items-center justify-center">
          <div className="relative">
            {/* Outer expanding rings */}
            <div className="absolute inset-0 animate-ping rounded-full bg-white opacity-25 h-48 w-48" />
            <div className="absolute inset-0 animate-ping rounded-full bg-white opacity-20 h-48 w-48 delay-75" />
            <div className="absolute inset-0 animate-ping rounded-full bg-white opacity-15 h-48 w-48 delay-150" />
            
            {/* Center icon */}
            <div className="relative bg-white rounded-full p-8 h-48 w-48 flex items-center justify-center">
              <CreditCard className="w-24 h-24 text-blue-600" />
            </div>
            
            <p className="text-white text-center mt-8 text-xl font-medium">
              Hold near reader
            </p>
          </div>
        </div>
      )}

      <div className="pb-20">
        <div className="p-4 max-w-md mx-auto space-y-4">
          {/* Header */}
          <div className="flex items-center justify-between mb-6">
            <h1 className="text-2xl font-bold text-gray-900">MongPay</h1>
            <img 
              src="/api/placeholder/40/40" 
              alt="Profile" 
              className="w-10 h-10 rounded-full"
            />
          </div>

          {/* Custom Card Image Area */}
          <div className="aspect-[1.586/1] bg-gray-200 rounded-xl overflow-hidden mb-4 relative">
            <div className="absolute inset-0 flex items-center justify-center text-gray-500">
              Upload your custom card image here
            </div>
          </div>

          {/* Tap to Pay Button */}
          <Button 
            className="w-full py-6 text-lg font-medium bg-blue-600 hover:bg-blue-700"
            onClick={handleTapToPay}
          >
            Tap to Pay
          </Button>

          {/* Balance Card */}
          <Card className="bg-gradient-to-br from-blue-600 to-blue-700">
            <CardContent className="pt-6">
              <div className="text-white">
                <p className="text-sm opacity-90">Available Balance</p>
                <h2 className="text-4xl font-bold my-2">$42,069.00</h2>
                <p className="text-sm opacity-90">@mongpay-user</p>
              </div>
            </CardContent>
          </Card>

          {/* Recent Activity */}
          <Card>
            <CardContent className="pt-6">
              <h3 className="font-semibold mb-4">Recent Activity</h3>
              <div className="space-y-4">
                {[
                  { name: 'Mong Market', amount: '-$420.69', date: 'Today' },
                  { name: 'Received from @friend', amount: '+$69.00', date: 'Yesterday' },
                  { name: 'Mong Groceries', amount: '-$89.99', date: 'Oct 25' }
                ].map((transaction, i) => (
                  <div key={i} className="flex items-center justify-between py-2">
                    <div className="flex items-center">
                      <div className="w-8 h-8 bg-gray-100 rounded-full flex items-center justify-center mr-3">
                        <History className="w-4 h-4" />
                      </div>
                      <div>
                        <p className="font-medium">{transaction.name}</p>
                        <p className="text-sm text-gray-500">{transaction.date}</p>
                      </div>
                    </div>
                    <span className={transaction.amount.includes('+') ? 'text-green-600' : ''}>
                      {transaction.amount}
                    </span>
                  </div>
                ))}
              </div>
            </CardContent>
          </Card>
        </div>
      </div>

      {/* Mobile Navigation Bar */}
      <div className="fixed bottom-0 left-0 right-0 bg-white border-t border-gray-200 px-6 py-2">
        <div className="flex justify-between items-center max-w-md mx-auto">
          <button className="flex flex-col items-center p-2 text-blue-600">
            <Home className="w-6 h-6" />
            <span className="text-xs mt-1">Home</span>
          </button>
          <button className="flex flex-col items-center p-2 text-gray-600">
            <History className="w-6 h-6" />
            <span className="text-xs mt-1">Activity</span>
          </button>
          <button className="flex flex-col items-center p-2 text-gray-600">
            <Send className="w-6 h-6" />
            <span className="text-xs mt-1">Send</span>
          </button>
          <button className="flex flex-col items-center p-2 text-gray-600">
            <User className="w-6 h-6" />
            <span className="text-xs mt-1">Profile</span>
          </button>
        </div>
      </div>
    </div>
  );
};

export default Dashboard;