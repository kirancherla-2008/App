# Clone and setup
git clone [your-repo-url]
cd silent-income-stream
npm install

# Build the app
npm run build
# For Android phone
npx cap add android

# For iPhone (requires Mac)
npx cap add ios
# Sync and run
npx cap sync

# Launch on your phone
npx cap run android    # For Android
# OR
npx cap run ios        # For iPhone
