// app/login/page.tsx
"use client";

import { useState } from "react";
import { useRouter } from "next/navigation";

export default function LoginPage() {
  const [email, setEmail] = useState("");
  const [password, setPassword] = useState("");
  const [error, setError] = useState("");
  const router = useRouter();

  const handleLogin = (e: React.FormEvent) => {
    e.preventDefault();
    setError("");

    // Simple frontend-only check — no backend, no API call
    if (!email || !password) {
      setError("Please enter both email and password");
      return;
    }

    // Mock "login" — just redirect to the dashboard
    router.push("/dashboard");
  };

  return (
    <div className="min-h-screen flex items-center justify-center bg-gradient-to-br from-indigo-950 via-purple-900 to-slate-900 px-4">
      <div className="w-full max-w-md">
        {/* Logo / Branding */}
        <div className="text-center mb-8">
          <h1 className="text-4xl font-bold text-white tracking-tight">
            🎮 GameCraft<span className="text-purple-400">AI</span>
          </h1>
          <p className="text-slate-400 mt-2">
            Generate cohesive game assets with AI
          </p>
        </div>

        {/* Login Card */}
        <div className="bg-slate-800/60 backdrop-blur-md border border-slate-700 rounded-2xl shadow-2xl p-8">
          <h2 className="text-xl font-semibold text-white mb-6">
            Welcome back
          </h2>

          <form onSubmit={handleLogin} className="space-y-4">
            <div>
              <label className="block text-sm font-medium text-slate-300 mb-1">
                Email
              </label>
              <input
                type="email"
                value={email}
                onChange={(e) => setEmail(e.target.value)}
                placeholder="you@example.com"
                className="w-full px-4 py-2.5 rounded-lg bg-slate-900/60 border border-slate-600 text-white placeholder-slate-500 focus:outline-none focus:ring-2 focus:ring-purple-500 focus:border-transparent transition"
              />
            </div>

            <div>
              <label className="block text-sm font-medium text-slate-300 mb-1">
                Password
              </label>
              <input
                type="password"
                value={password}
                onChange={(e) => setPassword(e.target.value)}
                placeholder="••••••••"
                className="w-full px-4 py-2.5 rounded-lg bg-slate-900/60 border border-slate-600 text-white placeholder-slate-500 focus:outline-none focus:ring-2 focus:ring-purple-500 focus:border-transparent transition"
              />
            </div>

            {error && (
              <p className="text-red-400 text-sm bg-red-950/40 border border-red-900 rounded-lg px-3 py-2">
                {error}
              </p>
            )}

            <button
              type="submit"
              className="w-full py-2.5 rounded-lg bg-purple-600 hover:bg-purple-500 text-white font-medium transition"
            >
              Sign In
            </button>
          </form>

          <button
            type="button"
            onClick={() => router.push("/dashboard")}
            className="w-full mt-4 py-2.5 rounded-lg border border-slate-600 hover:bg-slate-700/40 text-slate-300 font-medium transition"
          >
            Skip login (demo mode) →
          </button>

          <p className="text-center text-slate-400 text-sm mt-6">
            Don't have an account?{" "}
            <a href="/signup" className="text-purple-400 hover:text-purple-300 font-medium">
              Sign up
            </a>
          </p>
        </div>
      </div>
    </div>
  );
}
